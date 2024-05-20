# GHSL DATA

Hi! In assets folder you will find set of PNG converted GeoTIFF files originally from [human-settlement.emergency.copernicus.eu](https://human-settlement.emergency.copernicus.eu/download.php?ds=pop). Files have custom colorscheme (original Tiff are grayscale) and contain additional processing Image splitting and concatenation. All data epoch: 2025, resolution: 3, 30 and 90 arcsec, coordinate system: WGS84
* 3ss files originate from the original images with a resolution of 3 arcseconds, with dimensions 12000x12000 pixels. Each of these images is divided into 16 smaller images, each sized 3000x3000 pixels (arranged in a 4x4 grid). This process reduces a single PNG image, typically around 70MB in size, into 16 smaller images, each with a maximum size of around 5MB.
* 30ss files, on the other hand, are derived directly from the original images with a resolution of 30 arcseconds, with dimensions 1200x1200 pixels. These files undergo no transformation except for adjustments to the color scheme and conversion from TIFF to PNG format.
* 90ss files, they are created by combining and compressing 30ss files. Specifically, nine 30ss files arranged in a 3x3 grid are merged and compressed into a single 90ss file, maintaining a resolution of 1200x1200 pixels.

Metadata files:
