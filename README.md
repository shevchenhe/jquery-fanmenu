# jQuery.fanmenu.js

Mimicking Path's Fan Menu UX

## Note

This plugin is mostly inspired by nikesh's [Pie-Menu](http://nikesh.github.io/Pie-Menu/),
but i refactor the wholly code in a more flexible way!

## Usage

1. link jquery.fanmenu.js on your html document 
2. link jquery.fanmenu.css and custom the style you like
3. using the dom structure as below

Html

```html
	<div id='testMenu' class="fm_wrap" >
		<a class="fm_btntoggle" href="#" title="Toggle"><i>+</i></a>
		<ul class="fm_list">
			<li><a href="#"><i class="icon-user icon-white"></i></a></li>
			<li><a href="#"><i class="icon-heart icon-white"></i></a></li>
			<li><a href="#"><i class="icon-music icon-white"></i></a></li>
			<li><a href="#"><i class="icon-home icon-white"></i></a></li>
			<li><a href="#"><i class="icon-flag icon-white"></i></a></li>
		</ul>
	</div>
```

JavaScript

```js

	/* 1 - init the fan menu */
	$("#testMenu").fanmenu({
		'initAngle':0,
		'angleDisplay' : 90,
		'radius':100,
		'hideOnClick':true
	});
	
	/* 2 - close the menu manually */
	$("#testMenu").fanmenu('close');

	/* 3 - open the menu manually */
	$("#testMenu").fanmenu('open');

```

## Demo

[Live demo!](http://faso.me/jquery-fanmenu/)
