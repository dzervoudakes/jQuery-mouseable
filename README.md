# jQuery-mouseable

_A !DOCTYPE-agnostic reprieve from unreliable pseudo classes._

Dynamically adds hover and active classes to DOM elements for styling, removing the need for CSS :hover and :active pseudo classes.  Unlike pseudo classes, this method is !DOCTYPE-agnostic.

##### Example:

```
$("#mouseable-test").mouseable();
```

In the example above, the default hover class = "over" and the default active class = "down".

##### Example with custom hover/active classes:

```
$("#mouseable-test").mouseable({
	hoverClass: "foo",
	activeClass: "bar"
});
```

In the example above, the hover class is user-defined as "foo" and the active class is user-defined as "bar".

*This plugin is optimized for both mouse events and touch events.*
