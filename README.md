This repository downloads and clean [the World Clim data (version 2)](http://worldclim.org/version2) ([Fick and Hijmans (2017)](https://doi.org/10.1002/joc.5086)) for monthly average temperature and precipitation.

Prerequisite: Python 2.7

Run `code/download_data.py`. This downloads 12 TIFF files for each weather variable in the `/orig` folder.

These TIFF files turn out to be already clean. There is no need to clean these data files.
