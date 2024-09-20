## Grundaufbau
```javascript
const url = "SomeRandomURL"
fetch(url)
.then(response => response.json())
.then(data => {
	/// -- Daten Verarbeiten -- ///
)
```
## Get
```javascript
const url = "SomeRandomURL"
fetch(url)
.then(response => response.json())
.then(data => {
	/// -- Daten Verarbeiten -- ///
)
```

## Andere Methoden
```javascript
const url = "SomeRandomURL"
fetch(url, {
	  method: 'post/put/delete/get',
	  body: {randomData: "data"}
})
.then(response => response.json())
.then(data => {
	/// -- Daten Verarbeiten -- ///
)
```
## Die 4 Verschiedenen Methoden (CRUD)
_CRUD Steht für Create, Read, Update, Delete_
### Get (Read)
Daten holen
### Put (Update)
Daten Updaten
### Delete (Delete)
Daten Löschen
### Post (Create)
Daten einfügen