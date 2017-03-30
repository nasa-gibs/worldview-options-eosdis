<input type="hidden" autofocus>

# Version 1.4.0

## New Features

* Certain imagery layers (e.g. MODIS or VIIRS Corrected Reflectance and some other daytime layers) can now be viewed over the dateline/anti-meridian for the day prior to and after the current day. This allows for an unbroken view of the Pacific Ocean as observed by the satellites.
* Users can now view the data value under the cursor in the respective layer's legend/color bar.
* A marker or bounding box has been added to illustrate an event’s location shown in the Events feed.
* Icons have been added to differentiate between natural event categories in the Events feed.
* Auto-disable function which prevents a layer from being turned on if there is no imagery available for that date.
* Daymet Minimum and Maximum Air Temperature layers added

## Updates

* Migrated to OpenLayers 4 mapping library

---

# Version 1.3.6

## New Features

* Monthly MERRA and MERRA 2 Surface Skin Temperature and Surface Pressure layers
* Monthly GLDAS Total Precipitation Rate, Air Temperature, Soil Moisture and NLDAS Precipitation Total, Air Temperature and Soil Moisture layers
* Daily OMI UV Erythemal Daily Dose, Daily Rate and UV Index layers
* Weekly Aquarius Soil Moisture layers

## Updates

* Corrected end dates of non-daily layers

---

# Version 1.3.5

## New Features

* Added AMSR2 Soil Moisture Normalized Polarization Difference (Day and night) Layers
* Added AMSR2 Soil Moisture Single Channel Algorithm (Day and night) Layers
---


# Version 1.3.4

## New Features

* Added Daily OMI Standard layers including Sulfur Dioxide (Planetary Boundary layer), Aerosol Optical Depth (388 nm, Multi-Wavelength), Aerosol Single Scattering Albedo 388 nm, Near-UV), Ozone (DOAS), Ozone (TOMS-like) Nitric Oxide (Tropospheric Column)
* Added Monthly CERES Top-Of-Atmosphere (TOA) Flux, Surface Flux and Incoming Solar Flux layers 
* Added TRMM Lightning Imaging Sensor (LIS) and OrbView-1 OTD Lightning Flashes and Lightning Flash Rate layers
* Added Monthly, Annual and Seasonal Web Enabled Landsat Data (WELD) TOA reflectance for Alaska and Conterminous US (V1.5) and Surface Reflectance (NBAR) Global and NDVI (V3.0) layers.
* Added Daily and Monthly MOPITT Carbon Monoxide layers
* MODIS and VIIRS fires can now be displayed in the Arctic view

## Updates

* Fixed animation widget styling issues specific to Safari
* Fixed permalink of squashed palettes to retain max value
---

# Version 1.3.3

## New Features

* Added VIIRS Nighttime Imagery (Day/Night Band, Enhanced Near Constant Contrast) layer

## Updates

* Added Worldview stamp to animation GIFs
* Fixed bug that prevented borders and place names from being visible in animation GIFs
* Added option to slow animation speed down to 0.5 frames per second(fps). The previous minimum was 1 fps.
* Fixed accidental date change on map panning bug

---

# Version 1.3.2

## New Features

* GHRC SSMI Layers including Cloud Liquid Water, Water Vapor, Rain Rate, Surface Wind Speed for July 1987 – present
* NSIDC DMSP 5D-3 F17/SSMIS, DMSP 5D-3 F18/SSMIS Sea Ice Concentration (Polar projection only)
* NSIDC SAC-D Aquarius Soil Moisture layer
* Rolling 8-day MODIS Vegetation Indices layers – Normalized Difference Vegetation Index (NDVI) and Enhanced Vegetation Index (EVI) and descriptions
* Animation-GIF date stamp capability

## Updates

* Added a grunt task to relocate node_module dependencies within web/ directory
* Now if non-existent images are requested for the creation of an animation-GIF, they will be skipped
* Now filtering download links by file extension rather than CMR's "data" tag
* Added text to denote temporal coverage to the beginning of layer descriptions
---

# Version 1.3.1

## Updates

* Data download search now uses CMR in place of ECHO
* Fixed rotation error present on IOS devices
* Openlayers update to 19.1.x
* Releasing mouse click over timeline after dragging map no longer changes date
* Animation default start/end date guesses have been adjusted
* Animation is now dynamic/omittable in options configuration.
---

# Version 1.3.0-2

## Updates

* Fixed animation playback error

---

# Version 1.3

## New Features

* Worldview can now animate imagery with the animation feature!
  * A new button on the timeline opens the animation feature where it's possible to select start/end dates, frames per second, and whether to loop or not
  * The animation can be exported as a gif file by using the "Share Animation GIF" button in the same dialog
* The polar view now contain a widget to rotate the imagery

## Updates

* MODIS C6 Atmosphere products now have metadata descriptions

---

# Version 1.2.3

## Updates

* Added MODIS Cloud Top Height layers
* Defaulting to VIIRS Corrected Reflectance layer for Severe Storm events
* Fixed unexpected date changes when using arrow keys in text fields

---


# Version 1.2.2

## Updates

* Enhancements to Events feature:
  * Now showing place labels and borders when an event is selected
  * Map zooms further into wildfire and volcano events to show more detail
  * Wildfire events are now set to automatically display the next day, as these events often do not appear in the satellite imagery on the day they are reported
  * Not listing EONET earthquake, drought, and landslide events since they're not readily visible with current imagery
* Auto-setting resolution setting of image capture tool to match the map's current zoom level
* Fixed formatting of layer descriptions
* Fixed problem with "!" warning appearing next to layer item at incorrect zoom level in polar view

---

# Version 1.2.1

## Updates

* Atmosphere layers now display correctly under Scientific layers

---

# Version 1.2

## New Features

* Visually browse active natural hazards with the new "Events" tab!  Events are populated from the Earth Observatory Natural Event Tracker (EONET), http://eonet.sci.gsfc.nasa.gov/
* Added the following MODIS Collection 6 Atmosphere products from mission launch through the present: Cloud Effective Radius (standard, 3.7, and 3.7 PCL), Cloud Water Path (standard and PCL), Cloud Optical Thickness (standard and PCL)
* Updated the following MODIS Atmosphere products from Collection 5 to Collection 6 which are now available from mission launch through the present: Aerosol Optical Depth, Cloud Top Pressure, Cloud Top Temperature, Water Vapor


## Updates

* Now handling layers which have dual color palettes by upgrade to GIBS Colormap Schema v1.2
* Fixed loading on mobile devices with higher pixel densities
* Fixed SMAP orbit track labels, GCOM-W1 orbit track color
* Updated layer descriptions

---

# Version 1.1

## New Features

* Added the following MODIS C6 Atmosphere products: Aerosol Optical Depth 3km (3km, Land and Ocean), Deep Blue Aerosol Angstrom Exponent (Land), Dark Target Aerosol Angstrom Exponent (Ocean), Deep Blue Aerosol Optical Depth (Land), Merged DT/DB Aerosol Optical Depth (Land and Ocean), Cloud Multi Layer Flag, Cloud Phase Optical Properties, Cloud Fraction, Cloud Phase Infrared, Cloud Top Height
* Added orbit tracks for Landsat 8, ISS, GOSAT, and SMAP

## Updates

* GIBS endpoints have been updates for the new GIBS system
* Fixed an incorrect link for data download of Sea Ice Brightness Temperature
* Fixed a bug where the Data Download dialog was attaching itself to the Layer modal
* Fixed an issue with scrolling the timeline east/west with a mouse wheel
* Removed PO.DAAC SST 5 day layer
* Removed the degree signs from Kelvin in the legend
* Various layer descriptions / text updated
* Updated FAQ

---

# Version 1.0.1

## Updates

* Fixed a bug that still shows a product as added when it's removed
* Added a Data Download message for Terra/Aqua fires

---

# Version 1.0

## New Features

* Metadata has been added to many products in the product picker.
* Added AMSR-E Rain layers
* Added AMSR2 Sea Ice layers
* Added Suomi NPP Orbit tracks

## Updates

* MODIS/VIIRS fires are now correctly included in kmz image downloads
* The width of the product picker is now limited for best viewing results
* A link to the source code of Worldview is now directly on the Info menu
* Various bug fixes

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

# Version 0.9.0

## New Features

* New product picker has replaced the Add Layers tab:
* All layers are now ordered by measurement, then source (or instrument).
* Categories and Metacategories organize measurements.
* Related Orbital Tracks option now present when adding layers.
* Add Layers button added to the bottom of the Active Layers tab.
* Space created for adding Metadata to products.
* Added the following layers: SRTM, GHRSST, Suomi NPP / VIIRS, various new SMAP L3 Active/Passives, SMAP L4


## Updates

* The Active Layers and Data Download windows' height is now correctly calculated.
* Base Layers and Overlays are now one scrollable window instead of two.
* Overlays placement has switched with Base Layers to reflect the map's layer order.
* Download Selected Data button moved to the bottom of the Data Download tab window.
* Tour updates.

---

## Older Releases

See the <a href='https://github.com/nasa-gibs/worldview/releases' target='_blank'>
full history of release notes</a>
