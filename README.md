# GHSL DATA

Hi! In assets folder you will find set of PNG converted GeoTIFF files originally from [human-settlement.emergency.copernicus.eu](https://human-settlement.emergency.copernicus.eu/download.php?ds=pop). Files have custom colorscheme (original Tiff are grayscale) and contain additional processing Image splitting and concatenation. All data epoch: 2025, resolution: 3, 30 and 90 arcsec, coordinate system: WGS84
* 3ss files come form original 3 arcsec resolution 12000x12000 pixels images where each image was split on to 16(4x4) smaller images each 3000x3000 in pixel size. Thus reducing single PNG image with size ~70MB to 16 smaller size images each around 5MB max.
* 30ss files come from original 30 arcsec resolution 1200x1200 without any transformation, just colorscheme and Tiff to PNG conversion was applied.
* 90ss files are concatenation and compression of 30ss files. 3x3 30ss files are merged and compressed into single 90ss file with 1200x1200 pixel resolution.

