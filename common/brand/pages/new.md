<input type="hidden" autofocus>

# Version 0.9.0

## New Features

* New product picker
** All layers are now ordered by measurement, then source (or instrument).
** Categories and Metacategories organize measurements.
** Related Orbital Tracks option now present when adding layers.
** Add Layers button added to the bottom of the Active Layers tab.
** Space created for adding Metadata to products.

## Updates

* The Active Layers and Data Download windows' height is now correctly calculated.
* Base Layers and Overlays are now one scrollable window instead of two.
* Overlays placement has switched with Base Layers to reflect the map's layer order.
* Download Selected Data button moved to the bottom of the Data Download tab window.
* Tour updates.

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

# Version 0.8.10

## Updates

* Fixed a bug where data download results were not being filled in fully

---

# Version 0.8.9

## New Features

* Added capability to support 30m/px imagery
* Added ASTER GDEM Layers: Color Index, Color Shaded Relief, and Greyscale Shaded Relief
* Added a UI indicator and tooltip per layer to show when a layer is overzoomed
* Added SMAP L2/L3 Passive layers

## Updates

* Due to the base url change for shortened links, a (?) tooltip now exists to help users to migrate their saved links.

---

# Version 0.8.8

## Updates

* Fixed URL shortening bug

---

# Version 0.8.7

## New Features

* Added new SMAP layers: Sigma0, Sigma0 QA, Sigma0 RFI 

---

# Version 0.8.6

## New Features

* Added layer GCOM-W1 / AMSR2 Snow Water Equivalent.

---

# Version 0.8.5

## New Features

* Added new SMAP layers: Uncorrected Brightness Temperature, Faraday Rotation Angle.
* Added Data Download for AMSR-E and SMAP layers.

## Updates

* Data Download can now handle larger granules.
* Updated Documentation for Data Download.

---

# Version 0.8.4

## New Features

* Added new AMSR2 layers: Columnar Cloud Liquid Water, Columnar Water Vapor, Surface Preciptation Rate, Surface Rain Rate, Wind Speed.
* Added new orbit track: GCOM-W1

## Updates

* Fixed Earthdata links for content that was moved.

---

# Version 0.8.3

## Updates

* Updated for Earthdata 3.0.

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
