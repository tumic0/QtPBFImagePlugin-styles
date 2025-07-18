# QtPBFImagePlugin styles
Styles for Mapbox vector tiles (MVT) usable with
[QtPBFImagePlugin](https://github.com/tumic0/QtPBFImagePlugin).

There are (at least) eight incompatible MVT schemas out there:
- Esri
- Mapbox
- OpenMapTiles (MapTiler, Mapilion)
- Ordnance Survey
- Tilezen (HERE, Nextzen)
- VersaTiles
- WebVektor
- IGN

This repository contains Mapbox GL styles usable with QtPBFImagePlugin for
each schema. The styles are copies (sometimes with minor tweaks) of the original
styles created by Mapbox, OpenMapTiles, Apollo Mapping, Esri, ... before they
have started to use expressions. The OrdnanceSurvey and the VersaTiles style are
backports of the original styles without expressions.
