HTML Layout Grid Overlay
==================

This is an example package with a overlay image 
![overlay](https://github.com/topdown/Grid-Layout-Overlay/blob/master/src/img/100grid.png "Overlay")

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
	#grid {
	display:    block;
	position:   absolute;
	background: url('../img/100grid.png') repeat;
	z-index:    10000;
	width:      100%;
	height:     100%;
	min-height: 800px;
	margin:     0;
	padding:    0;

	top:        -12px; /* Adjust the Vertical position */
	left:       -6px; /* Adjust the Horizontal position */
	opacity:    .7; /* Adjust the opacity */
}

**Add the HTML after the opening body tag.**
	<div id="grid"></div>


This is a screen shot of the example files do their job.
![Example](https://github.com/topdown/Grid-Layout-Overlay/blob/master/grid-screenshot.png "Example")