# MODIS_SST
Processing code for MODIS sea surface temperatures to estimate surface and subsurface ocean temperatures near Sermilik Fjord

Please cite the paper below if you use this code and we highly recommend contacting the author (tasha.snow@colorado.edu) before using the code to ensure its reasonable application. 

The MODISsstExtraction file samples MODIS SSTs from the MODIS 4 km products and produces a daily time series for each sampling region (Irminger Current, East Greenland Coastal Current, and the "Shelf Trough" along the bathymetric trough leading to Sermilik Fjord).

The MOD29 file creates the sea ice masks for the SSTs, which is used in the Extraction file.

MODIStimeseries file uses the extracted MODIS SSTs and processes them as described in:

Snow, T., Straneo, F., Holte, J., Grigsby, S., Abdalati, W., & Scambos, T.(accepted). More than skin deep: sea surface temperature as a means of inferring Atlantic Water variability on the southeast Greenland continental shelf near Helheim Glacier. Journal of Geophysical Research: Oceans. doi: https://www.essoar.org/doi/abs/10.1002/essoar.10503490.1
