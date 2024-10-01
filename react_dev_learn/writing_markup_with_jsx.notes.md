# Writing markup with JSX

The markup syntax in React code is called JSX. The syntax is optional, but it is much more convenient to write than the plain-JavaScript-object variant.

JSX is stricter than HTML. Tags like `<br />` have to be closed manually. Components also can't return multiple JSX tags at the same level, in this case, all the tags must be wrapped in a shared parent tag. Alternatively, if there is no semantic tag to wrap JSX in for a return, an empty wrapper can be used (`<>...</>`).

Online conversion tools can be used to convert HTML into valid JSX.
