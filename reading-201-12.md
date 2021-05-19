### Read: 12 - Docs for the HTML <canvas> Element & Chart.js

Chart.js is a community maintained open-source library (it’s available on GitHub) that helps you easily visualize data using JavaScript. It’s similar to Chartist and Google Charts. It supports 8 different chart types (including bars, lines, & pies), and they’re all responsive. In other words, you set up your chart once, and Chart.js will do the heavy-lifting for you and make sure that it’s always legible.

#### The Charts.js API
All that is needed for the Charts.js API is the script included in your page along with a single node to render the chart.

General Configuration

These are some general configuration options for the charts.

* Responsive - defines responsive chart options that apply to all charts.
* Device Pixel Ratio - defines the ratio between display pixels and rendered pixels.
* Interactions defines options that reflect how hovering chart elements works.
* Options - scriptable and indexable options syntax.
* Colors - defines acceptable color values.
* Font - defines various font options.
* Performance - gives tips for performance-sensitive applications.
Chart.js can be used with ES6 modules, plain JavaScript and module loaders. Basically it is used for creating dynamic data driven charts for websites.

#### The Canvas API
The Canvas API provides a means for drawing graphics via JavaScript and the HTML element. It can also be used for animation, game graphics, data visualization, photo manipulation, and real-time video processing.

The Canvas API largely focuses on 2D graphics. The WebGL API, which also uses the element, draws hardware-accelerated 2D and 3D graphics.

#### Basic usage
At first sight a looks like the  element, with the only clear difference being that it doesn't have the src and alt attributes. The element has only two attributes, width and height which are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300px wide and 150px high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

#### Drawing shapes with canvas
only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. There are three functions that draw rectangles on the canvas:

* fillRect(x, y, width, height) - Draws a filled rectangle.
* strokeRect(x, y, width, height) - Draws a rectangular outline.
* clearRect(x, y, width, height) - Clears the specified rectangular area, making it fully transparent.

[<---Back](README.md)