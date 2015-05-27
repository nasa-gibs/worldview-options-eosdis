<input type="hidden" autofocus>

# Version 0.8.3

## New Features

* Added the following orbital tracks:
  * Cloudsat
  * SMAP
  * Suomi NPP
  * GCOM-W1
  * International Space Station
  * Landsat-8
  * GOSAT
* Back processed all orbital tracks to mission start

## Known Issues

* Internet Explorer 8 and below is not supported.
* Internet Explorer 9 has difficulties rendering the user interface under
  certain circumstances, though should remain usable.
* Custom color palettes are not supported on Internet Explorer or on Safari 5
  and earlier.
* On iOS, layers cannot be reordered
* WMS based layers (Population Density and Global Labels) can no longer be
  displayed properly in the older arctic projection (EPSG:3995).
* A mixed content warning may be displayed when using layers from external
  servers not using https.

---

# Version 0.8.2

## New Features

* Coordinate display can now be toggled between decimal degrees and
degrees, minutes, and seconds.
* Coordinates are now displayed in the image download crop window.
* Layers provided by the Socioeconomic Data and Applications Center (SEDAC)
are now available through image download.

---

# Version 0.8.1

## New Features

* When applying a color palette threshold, the color range can now be clamped
or squashed.

## Updates

* The ends of the timeline now have some additional padding.
* Animated zoom effect disabled when using Firefox.
* Graticule layer in the geographic projection can now have its visiblity
toggled.
* Parenthetical number of layers now updated when swtiching projections.

---

# Version 0.8.0

## New Features

* Map renderer upgraded to [OpenLayers 3](http://openlayers.org/).
* AMSR-E layers are now available in data download.

## Updates

* Image download now works on devices that are exactly 720 pixels in width.

---

## Older Releases

See the <a href='https://github.com/nasa-gibs/worldview/releases' target='_blank'>
full history of release notes</a>
