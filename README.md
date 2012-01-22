HTML Layout Grid Overlay
==================

I came up with this idea while trying to align form elements in a form that had different size inputs.

This is an example package with a overlay image 

![overlay](https://github.com/topdown/Grid-Layout-Overlay/blob/master/src/img/100grid.png?raw=true "Overlay")

It can be found in /src/img/100grid.png

Solid Black = 100px * 100px

Dashed Black = 50px * 50px

Solid Red = 10px * 10px


**The point of this is to create a grid for block alignment.**

The grid is created with a absolute / repeated CSS overlay.

To adjust the position of the grid for perfect alignment, adjust

In the src/css/style.css for the #grid selector.

Eg.

	top:        -12px; /* Adjust the Vertical position */

	left:       -6px; /* Adjust the Horizontal position */

	opacity:    .7; /* Adjust the opacity */


**Add the HTML after the opening body tag.**

	<div id="grid"></div>

This is a screen shot of the example files doing their job.
![Example](https://github.com/topdown/Grid-Layout-Overlay/blob/master/grid-screenshot.png?raw=true "Example")

[This Readme was created with PHP MD Editor](https://github.com/topdown/PHP-MD-Editor "PHP-MD-Editor")
