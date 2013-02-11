rot.js
======


ROguelike Toolkit

More info: http://ondras.github.com/rot.js

This fork intends to add image bitmap font support to rot.js, much like [libtcod](http://doryen.eptalys.net/data/libtcod/doc/1.5.1/html2/console_set_custom_font.html).
Right now, this is experimental and does only work for the provided terminal8x8 font.

Caution:
Problem: Unlike the upstream repo this fork only works if served on http, because of the use of image [security](http://simonsarris.com/blog/480-understanding-the-html5-canvas-image-security-rules).
Workaround: Serve the local directory via 
		python -m SimpleHTTPServer
and connect to http://localhost:8000