# HTML beginnings
Return to [Home Page](README.md)
Other pages: [Python](pythonbeginnings.md) | [Turtle Graphics](TurtleGraphics.md) | [JavaScript](JavaScript.md)

A few weeks into the _IT 1000_ course, we also learned how to code a bit of [HTML](https://en.wikipedia.org/wiki/HTML) in order to imbed a [Scalable Vector Graphics (SVG)](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics). HTML is a markup language that is used to be displayed on the web. We learned parts of HTML because a SVG must be embedded into the HTML to work.

![HTML Logo](https://images.app.goo.gl/WSeBXPxmV2SYDAHZ6)

This section of the course was meant to introduce us to concept of SVGs and the interworkings of webpages. SVGs are commonly used because they are:  
* vector based  
* easy to use with various languages (**W3C standard**)  
* can be used for various designs  

Some example code is shown here:
><html>
><body>
><h1 style="text-align:center;font-size:350%;font-family:optima;color:#25523B;">This is my first SVG.</h1>

><svg width="800" height="400">
	><rect x="300" y="10" rx="15" ry=:15" width="400" height="300" style="fill:yellow;stroke:lightblue;stroke-width:10;fill-opacity:0.5;strokeopacity:0.5" />
></svg>

><svg id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 194.83 146.39"><defs><style>.cls-1{fill:#fff;stroke:#231f20;stroke-miterlimit:10;stroke-width:7px;}</style></defs><polygon class="cls-1" points="52.1 103.19 6.8 103.19 75.97 6.38 162.21 142.89 36.04 142.89 122.96 6.38 188.25 103.19 52.1 103.19"/></svg>
></svg>

></body>
></html>

The output of this code looks like this in a web browser:
![SVG Screenshot](svgscreenshot.png)  
_(Note: the bottom of the full SVG is cut off due to the size of the image.)_
