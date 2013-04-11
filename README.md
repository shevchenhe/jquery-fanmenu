# Fan-Menu

Mimicking Path's Menu UX

## Note

This plugin is mostly inspired by nikesh's [Pie-Menu](http://nikesh.github.io/Pie-Menu/),
but i refactor the code in a more flexible way!

## Usage

1. link jquery.fanmenu.js on your html document 
2. link jquery.fanmenu.css and custom the style you like
3. using the dom structure as below

Html
```html
  <div id='outer_container' class="outer_container" >
		<a class="fm_btntoggle" href="#" title="Toggle"><span>Menu Toggle</span></a>
		<ul class="fm_list">
		  <li><a href="#"><span>Item</span></a></li>
		  <li><a href="#"><span>Item</span></a></li>
		  <li><a href="#"><span>Item</span></a></li>
		  <li><a href="#"><span>Item</span></a></li>
		  <li><a href="#"><span>Item</span></a></li>
		</ul>
	</div>
```

JavaScript
```html
	$('#outer_container').PieMenu({
		'starting_angel':0(Starting Angle in degree),
		'angel_difference' : 90(Displacement angle in degree),
		'radius':100 (circle radius in px),
	});	
```
[Live demo!](http://faso.me/jquery-fanmenu/)
