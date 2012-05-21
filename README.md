Raphaël + Flot = Raphlot
========================

An port of [Flot](http://code.google.com/p/flot/) to use the [Raphaël](http://raphaeljs.com/) APIs.

Where Flot produces raster images on a Canvas bitmap, Raphlot (via Raphaël) will produce SVG graphs where supported, and VML graphs on IE6/7/8.

Advantages of this approach:

* SVG/VML are vector formats, which is much better suited to drawing graphs.
* No need for excanvas
* Looks better at arbitrary zoom levels (important for multitouch devices)
* IE9 will support hardware-accelerated SVG

Disadvantages:

* It's currently a little slower than Canvas
* No support on Android
