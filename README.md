seeessess (css)
===============

A small PHP CSS preparser with no crazy server-side dependencies to 
install/configure in order to use it.

The intention is that this should perform all preparsing in a single pass 
whilst streaming out the CSS file to the browser and should (hopefully) 
never eat loads of RAM or CPU time. 

Usage
-----

Simply place in the root of your ./css directory and include your css files with a ? infront of the filename like so:

	<link href='./css/?layout.css' rel='stylesheet' type='text/css' />

