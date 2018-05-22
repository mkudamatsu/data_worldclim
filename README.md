This repository downloads and clean [the World Clim data (version 2)](http://worldclim.org/version2) ([Fick and Hijmans (2017)](https://doi.org/10.1002/joc.5086)) for monthly average temperature and precipitation at the 30 second resolution.

Prerequisite: Python 2.7

Run `code/download_data.py`. This downloads 12 TIFF files for each weather variable in the `/orig` folder.

These TIFF files turn out to be already clean. There is no need to clean these data files.

To download other weather variables, edit `code/download_data.py` to include the URL for them.
