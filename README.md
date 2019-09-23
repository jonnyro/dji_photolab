Introduction
------------
I regularly need to parse elevation data from JPEGs produced by DJI drones.

DJI produced JPEGs encode data in both the EXIF and XMP areas of the JPEG.

This library has a series of helper routines for extracting the elevation
and imagery data from folders of JPEG files.

This source tree is divided into three parts

1. analysis - a jupyterlab docker image which instantiates this library and provides figure generation.
2. test\_data - sample images with JPEG metadata.
3. src - source of the library.

References
----------
1. https://en.wikipedia.org/wiki/Exif
2. https://en.wikipedia.org/wiki/Extensible\_Metadata\_Platform
