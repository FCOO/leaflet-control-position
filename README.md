# leaflet-control-position
Leaflet control for zooming and panning to a lat/lon 
position input in two text boxes. You can use the 
lat/lon formats supported by:

https://github.com/dbarbalato/magellan/

## Demo
http://jblarsen.github.io/leaflet-control-position/

## Requirements
Leaflet, Magellan and noty (easy to rip out).

http://leafletjs.com/
https://github.com/dbarbalato/magellan/
http://ned.im/noty/

## Usage
Install the dependencies and include the Javascript and CSS
file in this repository in your application (note that the 
CSS file uses an image from the images directory):

You can then just add the control to your Leaflet map:

        map.addControl(new L.Control.Position);
