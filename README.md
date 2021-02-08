![AutoAdjustTest](images/title.png)
## Introduction

The Fengyun-2 series of satellites are geostationary satellites that deliver images of earth once per hour. The delivery consists of S-VISSR data: 1 VIS, 3 IR and 1 Watervapour images. They are delivered on the L-band frequency 1687.5 MHz. If you are within the footprint of the satellite, it is possible to receive with at least a 1.2m dish and Nooelec Saw filter.
As there are both VIS and IR channels, it is possible to create false colour images by using CLUT (colour look up table).

## Image data
Below are the following images and their resolutions delivered by the satellite.
![AutoAdjustTest](images/FY_images.png)

## Image data resolutions
Channel | Type | Resolution |
------------ | ------------- | ------------- |
1 | IR | 2291 x 2501
2 | IR | 2291 x 2501
3 | WV | 2291 x 2501
4 | IR | 2291 x 2501
5 | VIS | 9160 x 10004

## Requirements
To use the CLUT requires the following:
Name | For | Author | Source
------------ | ------------- | ------------- | ------------- |
Decoder | Decodes the S-VISSR data | | 
GeoSatSignal | Applies the CLUT from a file |  |
