# MODIS (Terra/Aqua) Aerosol Optical Depth

MODIS Aerosol Optical Depth at 0.55 µm is reported using two independent dark surface algorithms over both Ocean (best) and Land (corrected) with best quality data (QA Confidence Flag = 3). The retrieval method uses MODIS Bands 1-7 plus Band 26 (cirrus detection) to report the extinction AOD due to the combined effects of absorption and scattering. 

This combined ocean/land algorithm takes advantage of the MODIS wide spectral range and high spatial resolution with daily global coverage (e.g., 500m resolution at 0.47μm and 2.12μm; 250m resolution at 0.66μm and 0.86μm; 1 km resolution at 1.38μm). These unique MODIS characteristics allow excellent cloud rejection while maintaining high statistics of cloud free pixels. Spectral and spatial characteristics are combined to report estimated AOD at 10km resolution.

The method is not applied over sunglint ocean regions or bright (desert) land regions. Note that there is a complimentary Deep Blue Algorithm for bright land retrievals.

Reference: http://modis-atmos.gsfc.nasa.gov/_docs/ATBD_MOD04_C005_rev2.pdf
