CSS Variables
Store value in one place and re-use it later.

declare: --varName:value 
access: property:var(--varName);

example
:root {
    --primaryColor: #fff
}
var(--primaryColor);

Scope
:root{} === global
element === local

FontAwesome icons
-free icons, straight forward syntex

text-shadow/box-shadow -> use web sites, to autogenerate
https://cssgenerator.org/text-shadow-css-generator.html

Browser prefixes for compatibility
https://caniuse.com/css-grid
http://shouldiprefix.com/

Semantic HTML
https://www.w3schools.com/html/html5_semantic_elements.asp
<nav> vs <div>
- content is more defined with <nav>, but can be done with divs.

object-fit: cover, contain, fill, none, scale-down
- resize image to fit its container, (example: different image sizing)

Emmet 
h1 {ahoj}
h1>li*6{$ hello world}

:is() / :not()
-write less code.
/* Selects any paragraph inside a header, main
   or footer element that is being hovered */
:is(header, main, footer) p:hover {
  color: red;
  cursor: pointer;
}

/* The above is equivalent to the following */
header p:hover,
main p:hover,
footer p:hover {
  color: red;
  cursor: pointer;
}

HSL (Hue-saturation-value)
values 0 to 360
https://hslpicker.com/#301ce3
