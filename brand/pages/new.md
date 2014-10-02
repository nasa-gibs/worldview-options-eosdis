<input type="hidden" autofocus>
# New in Version 0.7

* New timeline interface to explore imagery over a larger time span
    * Selected day can be changed by clicking on the timeline or dragging
    the selection marker.
    * Temporal area of interest can be changed to weeks, months, years,
    or decades.
    * Easily go to the next or previous day using buttons on the interface
    or the arrows on the keyboard. Hold down to continuously change the
    current day.
    * A bar on the timeline indicates the temporal ranges of the layers
    being shown on the map.
    * A specific date can be typed into the text boxes on the left side
    of the timeline.
* The opacity for each layer can now be adjusted.
* Hovering over color legends now displays data values for that color.
* The maximum and minimum values can now be adjusted for overlays with
  color legends.
* In image download, additional files can now be downloaded to assist in
  geo-referencing the image in GIS applications.

---

## Updates

* Image download
    * Image artifacts no longer appear in base layers for GeoTIFF or PNG
    files.
    * A time parameter is now embedded into downloaded KMZ files to allow playback
    of images over time in Google Earth.
    * Base layers that are completely obscured by other base layers are no
    longer visible.
* The "data not available" message is no longer incorrectly shown when
  crossing certain month boundaries.
* The permalink format has been updated. Old permalinks are still supported.
* Missing color legends for certain layers have been added.  
* User feedback is now submitted through an online form rather than direct
  email.
* Various bugfixes and user interface updates.


---

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

## Older Releases

See the <a href='https://github.com/nasa-gibs/worldview/releases' target='_blank'>
full history of release notes</a>
