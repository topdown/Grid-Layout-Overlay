HTML Layout Grid Overlay
==================

This is an example package with a overlay image 

![overlay](https://github.com/topdown/Grid-Layout-Overlay/blob/master/src/img/100grid.png?raw=true "Overlay")

It can be found in /src/img/100grid.png

**The point of this is to create a grid for block alignment.**
The grid is created with a absolute / repeated CSS overlay.

To adjust the position of the grid for perfect alignment, adjust
top:
left:
and for opacity
opacity:
In the src/css/style.css for the #grid selector.
Eg.
	top:        -12px; /* Adjust the Vertical position */
	left:       -6px; /* Adjust the Horizontal position */
	opacity:    .7; /* Adjust the opacity */

**Add the HTML after the opening body tag.**
&lt;div id="grid"&gt;&lt;/div&gt;

This is a screen shot of the example files do their job.
![Example](https://github.com/topdown/Grid-Layout-Overlay/blob/master/grid-screenshot.png?raw=true "Example")

[This Readme was created with PHP MD Editor](https://github.com/topdown/PHP-MD-Editor "PHP-MD-Editor")