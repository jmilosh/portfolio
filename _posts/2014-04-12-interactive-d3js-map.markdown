---
date: 2014-04-12
layout: post
title: Zoomable D3.js Interactive Map
categories:
- d3.js
- python
---

[![Interactive D3.js map]({{ "/images/mariposa-map.png" | prepend: site.baseurl | prepend: site.url }})](http://janmilosh.github.io/adjuster-map/)

This zoomable interactive [map](http://janmilosh.github.io/adjuster-map/) was built with [D3.js](http://d3js.org/) for an insurance adjusting service website. Clicking on a state causes it to zoom to fit the map area. There is a tooltip feature that shows the number of insurance adjusters in a city (on hover).

I also wrote a Python script to retrieve the adjuster data from an adjuster portal API and to retrieve geodata from Google's API. This data is processed with Python and printed to a CSV file which is then referenced in the D3.js code.

The map is in service [here](http://www.mariposaltd.com/index.php?/services/coverage).