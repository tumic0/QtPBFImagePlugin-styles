# QtPBFImagePlugin styles
Styles for Mapbox vector tiles (MVT) usable with
[QtPBFImagePlugin](https://github.com/tumic0/QtPBFImagePlugin).

There are (at least) four incompatible MVT schemas out there:
- Mapbox
- OpenMapTiles (eg. MapTiler, Mapilion)
- Tilezen (eg. HERE, Nextzen)
- Ordnance Survey

This repository contains Mapbox GL styles usable with QtPBFImagePlugin for
each schema. The styles are usualy copies (sometimes with minor tweaks) of
the original styles created by Mapbox, Openmaptiles or Apollo Mapping before
they have moved to the new style format (expressions). The OrdnanceSurvey
style is a backport of the official OS style.
