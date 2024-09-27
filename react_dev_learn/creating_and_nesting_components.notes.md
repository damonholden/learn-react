# Creating and nesting components

React applications consist of components. A component is a piece of user interface that, as a unit of code, carries it's own logic and markdown.

Components can vary in size - they can be as small as a button and as large as an entire webpage.

React components are JavaScript functions that return markup:

```JSX
function MyButton() {
	return <button>I'm a button</button>
}
```

Components can be nested inside other components:

```JSX
function MyApp() {
	return (
		<div>
			<h1>Welcome</h1>
			<MyButton />
		</div>
	)
}
```

Components must start with capital letters to distinguish them from HTML tags - which are lowercase.
