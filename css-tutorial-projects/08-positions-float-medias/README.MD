FLOATS = NOWADAYS USED FOR designed for wrapping text around images
USE GRID OR FLEXBOX for layouting purposes.

Positions: static (default, always positioned according to the normal flow)
relative (relative to it's normal position unlocks -> top, bottom, left, right) 
absolute (relative to parent with position relative(body if not stated otherwise, body is always relative), will use other content to fill)
relative vs abstract = don't place other element as replacement
fixed: relative to viewport (screen), will use other content to fill 
sticky: toggles between relative and fixed once the position is met in the viewport then it sticks atleast one value of top, left, bottm, right.

MEDIA QUERIES
responsive design, mobile first (easier than desktop to mobile)
min-width
max-width

@media screen and (min-width: 576px) 

Z-index
0 default
does not work on position: static
basicaly a layering, which element is seen first if they are overlapping (lower to upper)

::Before ::After
Created element and inserts before or after CONTENT
- doenst work on img (content itself)
content:'' required (or add width/height to show)

p::before {
    content: 'bla'
}

Isolate img in div for ::before, ::after and make it display: block.

Inset property
shorthand for top, right, bottom left properties.
