# Leaflet Slider Template

## What is this?
This is a simple template to create projects that can compare two maps using a before-and-after-style slider tool.

Use two maps side by side, or as in the default version of the template, show two sets of tiles over a base map. Slider works in Chrome, Safari, Firefox and IE, and is responsive and mobile-friendly. See a published project [using this template here](http://interactive.wbez.org/elections/2015/mayoral-dot-map/).

## What it uses
* [leaflet](http://leafletjs.com/) for displaying the maps
* [bootstrap](http://getbootstrap.com/) as a mobile-friendly framework

## How to use it
* Substitute links to your two map layers for tileLayerRight and tileLayerLeft variables in the javascript, or load in a [geojson layer](http://leafletjs.com/reference.html#geojson) instead 
* Add your layer labels to the divs with classes "left" and "right". Customize styles as you see fit, but note that any changes to the slider need to be replicated for Chrome, Firefox and IE.