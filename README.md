# Code Style Guide

## CSS
### Declaration order
As per https://github.com/necolas/idiomatic-css, and http://codeguide.co/#css-declaration-order.

```css
.declaration-order {
	/* Special */
	content: ;

	/* Positioning */
	position: ;
	top: ;
	right: ;
	bottom: ;
	left: ;
	z-index: ;
	
	/* Display & Box-model */
	display: ;
	overflow: ;
    box-sizing: ;
	float: ;
	clear: ;
	width: ;
	height: ;
	min-width: ;
	min-height: ;
	max-width: ;
	max-height: ;
	padding: ;
	border: ;
	margin: ;
	
	/* Typography */
	font-size: ;
	font-family: ;
	font-style: ;
	line-height: ;
	color: ;
	text-align: ;
	vertical-align: ;
	text-indent: ;
	text-decoration: ;
	text-transform: ; 
	quotes: ;
	
	/* Visual */
	backface-visibility: ;
	background-color: ;
	background-image: ;
	background-position: ;
	background-repeat: ;
	background-cover: ;
	border-radius: ;
	opacity: ;
	outline: ;
	text-shadow: ;
	
	/* Animation and Transformation */
	animation: ;
	transition: ;
	
```

## HTML

Never line break content within text level elements.

```html
Good
<span>Text</span>

Bad

<a href="#">
  Text
</a>
```


## PHP

### Control Structures

Use curly braces `{ }` within PHP only files, and use the colon `:` varient with blocks of HTML


