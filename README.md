# Get me to Bournemouth

Get me to bournemouth is a one button app (website) which gets you to Bournemouth.

**[Try out 'Get me to Bournemouth' here](https://harrywood.co.uk/get-me-to-bournemouth)**
 
Click 'go' and it will detect your location and tell you how to travel to Bournemouth using [TransportAPI's public transport journey planning API](https://developer.transportapi.com/documentation/public-journey-planning).

## Hack Bournemouth ##

This was a one day hack developed for an event called '[Hack Bournemouth](http://hackbmth.org)' 

## How it works ##

The site is just javascript and HTML using...
* [TransportAPI's public transport journey planning API](https://developer.transportapi.com/documentation/public-journey-planning) in 'region=southeast' mode (using Traveline Southeast at the back end)
* Open licensed ODbL maps from [OpenStreetMap.org](http://openstreetmap.org)
* Tiles from the 'standard' OpenStreetMap tile server CC-BY-SA ([usage policy](http://wiki.openstreetmap.org/wiki/Tile_usage_policy))
* Map presentation javascript library is [LeafletJS](http://leafletjs.com)
* [jQuery](http://jquery.com) for ajax and DOM.
* [A photo by Chris Downer of Bournemouth](http://www.geograph.org.uk/photo/509151) cc-by-sa.2.0  - This is current at the top of the [wikipedia article on bournemouth](http://en.wikipedia.org/wiki/Bournemouth) (I didn't find many open licensed photos of Bournemouth in the sunshine!) - Used GIMP to modify this one to be yellow
* I copied in a [Haversine formula in Javascript from rosettacode](http://rosettacode.org/wiki/Haversine_formula#JavaScript]). This snippet is GPL licensed.

## License: Public domain

**Public domain**

I'd like to make the code easy to re-use if anyone wants to, hence public domain (or CC0 or WTFPL if you prefer). In this case I haven't really done much. It's a pretty simple mash-up. So it's fine to just take my code without crediting me, and I'd encourage you to do so. However...

* Desecribed above are a bunch of (awesome) libraries and resources which are not bundled in this repo. Obviously not covered by this license statement, though they're generally open licensed under various licenses.
* Also described above, I've used an open licensed photo image and in the code there is a haversine formula which is under GPL

