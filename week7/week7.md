Interactive Journalism - Advanced Data & Coding module
========================================================

Module code: JOM299

d3.js, the king of viz on the web

A definition
========================================================

> D3 allows you to bind arbitrary data to a Document Object Model (DOM), and then apply data-driven transformations to the document.

*Source: d3js.org*

The power of selections
========================================================

```javascript
var paragraphs = document.getElementsByTagName("p");
for (var i = 0; i < paragraphs.length; i++) {
  var paragraph = paragraphs.item(i);
  paragraph.style.setProperty("color", "white", null);
}
```
is, in d3 world:

```javascript
d3.selectAll("p").style("color", "white");
```

d3
========================================================

> D3’s vocabulary of graphical marks comes directly from web standards: HTML, SVG, and CSS.

> D3 is easy to debug using the browser’s built-in element inspector: the nodes that you manipulate with D3 are exactly those that the browser understands natively.

*Source: d3js.org*


========================================================

![](https://media.giphy.com/media/3oz8xPjPPvOwrGjip2/giphy.gif)

Why d3
========================================================

https://www.dashingd3js.com/why-build-with-d3js

First steps
========================================================

https://www.dashingd3js.com/d3js-first-steps

Blockbuilder
========================================================

> The whole point of this project is to make it easier for you to make blocks. Blocks are the de-facto way of sharing visualizations and code samples in the d3.js community. Invented and hosted by Mike Bostock, blocks are key to realizing the power of examples.

http://blockbuilder.org/

![](img/blockbuilder.png)

d3
========================================================

http://blockbuilder.org/basilesimon/c82b5d491cb5108f83172dc47d9f056c

http://blockbuilder.org/basilesimon/191de6a2bb164ea53e88593750ee0e5d

d3
========================================================

http://alignedleft.com/tutorials/d3/making-a-bar-chart

https://github.com/d3/d3/wiki/Tutorials

http://christopheviau.com/d3_tutorial/

https://bl.ocks.org/mbostock/3885304

http://bl.ocks.org/d3noob/b3ff6ae1c120eea654b5


