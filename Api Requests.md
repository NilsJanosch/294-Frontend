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
## Als Async Methode Exportieren
_So haben wir es gelernt_
```javascript
const url = "SomeRandomURL"

export async function fetchSomething() {
	const response = await fetch(url)
	if (!response.ok) {
		return Promise.reject(response.statusText)
	}
	const data = await response.json()
	return data
	}
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