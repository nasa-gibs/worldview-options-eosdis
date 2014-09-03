<input type="hidden" autofocus>
# New in Version 0.7

* New timeline interface to explore imagery over a larger time span.
  Temporal area of interest can be changed to weeks, months, years,
  or decades.
* Selected day can be changed by clicking on the timeline or dragging
  the selection marker.
* Easily go to the next or previous day using buttons on the interface
  or the arrows on the keyboard. Hold down to continuously change the
  current day.
* A bar on the timeline indicates the temporal ranges of the layers
  being shown on the map.
* A specific date can be selected by textual input.  
* The day, month, or year can be adjusted in increments by using buttons
  that appear when hovering over the date label.
* The opacity for each layer can now be adjusted
* Hovering over color legends now displays data values for that color
* The maximum and minimum values can now be adjusted for overlays with
  color legends.
* In image download, additional files can now be downloaded to assist in
  geo-referencing the image in GIS applications.

---

## Updates

* Improved user interface.
* Larger checkboxes are used in the add layers list.
* Image download now supports custom palettes.
* Image artifacts no longer appear in base layers when using image download
  with GeoTIFF or PNG files.
* A time parameter is now given when downloading KMZ files.
* Base layers that are completely obscured by other base layers are no
  longer visible when using image download.  
* On mobile devices, drop down menus can be closed by tapping elsewhere
  on the screen.
* The "data not available" message is no longer incorrectly shown when
  crossing certain month boundaries.
* Additional layers added to the various application areas of interest.
* Data download and orbit tracks now indicate that times are in
  Universal Coordinated Time (UTC)
* The application window no longer pulls slightly off the screen when reaching
  the end of scroll lists
* The permalink format has been updated. Old permalinks are still supported.
* Missing color legends for certain layers have been added.  
* Integration with the standard Earthdata Feedback module.

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
