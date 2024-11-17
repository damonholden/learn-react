# Adding styles

In React, you can specify a CSS class for an element with the `className` prop:

```JSX
<img className="avatar" />
```

This is synonymous to HTML's class attribute:

```HTML
<img class="avatar"/>
```

The difference exists because in JavaScript `class` is a reserved keyword for defining class's.

CSS is applied the exact same way in a CSS file:

```CSS
.avatar {
	border-radius: 50%;
}
```

There is no prescribed way to do styling in React. In the simplest case, you would simply add a `<link>` tag to a HTML file. However, a build tool or framework being used with React might have a prefered way of doing styling.
