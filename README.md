-Scalable-Vector-Graphics--SVG-Clock
====================================
"SVG is an XML grammar for graphics. The word 'vector' in its name indicates that it is funcdamentally 
different from raster image formats, such as GIF, JPEG, and PNG, that specify a matrix of pixel values. Instead, an SGV
'image' is a precise, resolution-independent (hence 'scalable') description of the steps necessary to draw the desired
graphic." - "JavaScript - The Definitive Guide" by David Flanagan, Pag. 622, O'Reilly.

In addition to simple shape-drawing primitives, it includes support for arbitrary curves, text, and animation.
SVG graphics can even incorporate JavaScript scipts and CSS stylesheets to add behavior and presentation information.

For full details about SVG, visit the specification maintained by the W3C at http://www.w3.org/TR/SVG/

For this simple example of the use of SVG, I will recreate Example 21-3 from 
"JavaScript - The Definitive Guide" by David Flanagan. This example can be found on page 628.

We will start with a static SVG image of a clock embedded in the HTML and then manipulate the image, making it transform
with a JavaScript funciton. The static clock hand will rotate by appropriate angles so that the clock displays the
current time.
