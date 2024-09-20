_UseState wird genutzt, um Daten dynamisch in die Website zu laden, z.B. einen Counter._

Usage Beispiel:
```javascript
	const [count, setCount] = useState(0)

	const handleClick = (e) => {
		setCount(count + 1)
	}

	return (
		<>
			<span>{count}</span>
			<button onClick={handleClick}>+1</button>
		</>
	)
```
