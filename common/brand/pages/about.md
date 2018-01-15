<div class="right"><div class="caption">Version @BUILD_VERSION@</div></div>

# Welcome to @NAME@

This tool from NASA's [EOSDIS](https://earthdata.nasa.gov/about) provides the capability to interactively browse global, full-resolution satellite imagery and then download the underlying data. Most of the 400+ available products are updated within three hours of observation, essentially showing the entire Earth as it looks "right now".  This supports time-critical application areas such as wildfire management, air quality measurements, and flood monitoring. Arctic and Antarctic views of several products are also available for a "full globe" perspective. Browsing on tablet and smartphone devices is generally supported for mobile access to the imagery.

<div class="right">
  <a href="https://earthdata.nasa.gov/gibs" class="gibs-logo"></a>
  <div class="caption gibs-caption">Powered by GIBS</div>
</div>

@NAME@ uses the [Global Imagery Browse Services (GIBS)](https://earthdata.nasa.gov/gibs) to rapidly retrieve its imagery for an interactive browsing experience. While @NAME@ uses [OpenLayers](http://openlayers.org/) as its mapping library, GIBS imagery can also be accessed from Google Earth, NASA World Wind, and several other clients. We encourage interested developers to build their own clients or integrate NASA imagery into their existing ones using these services.

[Frequently Asked Questions](https://earthdata.nasa.gov/faq/worldview-gibs-faq)

<hr/>

## Imagery Use

NASA supports an [open data policy](http://science.nasa.gov/earth-science/earth-science-data/data-information-policy/) and we encourage publication of imagery from @NAME@; when doing so for image captions, please cite it as "NASA @NAME@" and also consider including a direct link to the imagery in Worldview to allow others to explore the imagery.

For acknowledgment in scientific journals, please use: "We acknowledge the use of imagery from the NASA @NAME@ application (https://worldview.earthdata.nasa.gov/) operated by the NASA/Goddard Space Flight Center Earth Science Data and Information System (ESDIS) project."

<hr/>

## Acknowledgements

*  Near real-time data is courtesy of [LANCE](https://earthdata.nasa.gov/lance) data providers:
  * [AMSR SIPS](https://earthdata.nasa.gov/about/science-system-description/eosdis-components/lance/about-amsr2-sips)
  * [GES DISC](https://earthdata.nasa.gov/about/science-system-description/eosdis-components/lance/about-ges-disc)
  * [MODAPS](https://earthdata.nasa.gov/about/science-system-description/eosdis-components/lance/about-modaps)
  * [OMI SIPS](https://earthdata.nasa.gov/about/science-system-description/eosdis-components/lance/about-omi-sips)
  * [FIRMS](https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms)
* Ocean color and sea surface temperature products provided by [OB.DAAC](http://oceancolor.gsfc.nasa.gov/) and [PO.DAAC](http://podaac.jpl.nasa.gov/).
* Precipitation products provided by [Precipitation Processing System (PPS)](http://pps.gsfc.nasa.gov/) and [AMSR SIPS](https://earthdata.nasa.gov/about/science-system-description/eosdis-components/lance/about-amsr2-sips).
* Freeze/Thaw products, soil moisture and related products supplied by [NSIDC DAAC](http://nsidc.org/daac).
* Socioeconomic layers supplied by [SEDAC](http://sedac.ciesin.org/).
* Digital Elevation Model layers supplied by [LP DAAC](https://lpdaac.usgs.gov/).
* Orbit tracks provided by [space-track.org](https://www.space-track.org).
* Polar coastlines and graticules courtesy of [SCAR Antarctic Digital Database](http://www.add.scar.org/), [OpenStreetMap](http://www.openstreetmap.org/), and [PolarView](http://www.polarview.aq/).
* Coastlines, borders, roads, and place labels courtesy of [OpenStreetMap](http://www.openstreetmap.org/) and [Natural Earth](http://www.naturalearthdata.com/). This data is available under the [Open Database License](http://www.openstreetmap.org/copyright). &copy; OpenStreetMap contributors.
* Natural events database is provided by the [Earth Observatory Natural Event Tracker (EONET)](https://eonet.sci.gsfc.nasa.gov/).
* User-selectable color palettes are primarily derived from [NEO](http://neo.sci.gsfc.nasa.gov/).
* The imagery ingest and serving system (GIBS) is built by NASA/JPL and operated by NASA/GSFC.
* @NAME@ is built by the NASA/GSFC [Earth Science Data and Information System (ESDIS) Project](https://earthdata.nasa.gov/about/esdis-project). We are grateful for the many third-party projects we depend on which are listed in [our package.json file](https://github.com/nasa-gibs/worldview/blob/master/package.json) under "dependencies".

<hr/>

## Disclaimer

The information presented through this interface is provided "as is" and users bear all responsibility and liability for their use of the data. Please read the [full disclaimer](https://earthdata.nasa.gov/earth-observation-data/near-real-time/citation#ed-lance-disclaimer).

<hr/>

## License

Copyright &copy; 2013 - 2018 United States Government as represented by the Administrator of the National Aeronautics and Space Administration. All Rights Reserved.

This software is licensed under the [NASA Open Source Software Agreement, Version 1.3](https://ti.arc.nasa.gov/opensource/nosa/). Source code is available on [the NASA GIBS GitHub](https://github.com/nasa-gibs/worldview).

<hr/>

@BUILD_TIMESTAMP@ <br/>
Development Lead: [Benjamin King](mailto:benjamin.a.king@nasa.gov) <br/>
Responsible NASA Official: [Ryan Boller](mailto:ryan.a.boller@nasa.gov)
