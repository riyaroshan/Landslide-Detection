# Landslide-Detection
Through this project, we will attempt to detect the landslides at the early stages using deep learning techniques by training a model which will take the conditions required for landslides to occur as input.

## Dataset
For this project, we have decided to use the the Landslide4Sense data  which consists of the training, validation, and test sets containing 3799, 245, and 800 image patches, respectively. Each image patch is a composite of 14 bands that include:
Multispectral data from Sentinel-2: B1, B2, B3, B4, B5, B6, B7, B8, B9, B10, B11, B12.
Slope data from ALOS PALSAR: B13.
Digital elevation model (DEM) from ALOS PALSAR: B14.
All bands in the competition dataset are resized to the resolution of ~10m per pixel. The image patches have the size of 128 x 128 pixels and are labeled pixel-wise.
