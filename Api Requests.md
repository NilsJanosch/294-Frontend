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
## Die 4 Verschiedenen Methoden
### Get
Daten holen
### Put
Daten Updaten
### Delete
Daten Löschen
### Post
Daten einfügen