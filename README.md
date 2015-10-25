Leaflet Coordinates Control
===========================
Captures mouseclick and displays its coordinates with easy way to copy them.

Jack's Demo
----
http://jackdougherty.github.io/Leaflet-Coordinates-Control/

How to use
----------
	var c = new L.Control.Coordinates();

	c.addTo(map);

	map.on('click', function(e) {
		c.setCoordinates(e);
	});
