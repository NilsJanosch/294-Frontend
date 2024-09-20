_UseEffect ist eigentlich ein "Beobachter" einer Variable, wenn die Variable sich verändert, wird der definierte Code ausgeführt._

Usage Beispiel:
```javascript
	const [count, setCount] = useState(0)

	const handleClick = (e) => {
		setCount(count + 1)
	}

	useEffect(() => {
		/// -- Code, der ausgeführt wird -- ///
		console.log("Die Variable \"Count\" wurde verändert und hat jetzt den Wert: " + count)
	}, [count]) // Wir wollen ein Signal erhalten, sobald die Variable "count" verändert wird

	return (
		<>
			<span>{count}</span>
			<button onClick={handleClick}>+1</button>
		</>
	)
```
