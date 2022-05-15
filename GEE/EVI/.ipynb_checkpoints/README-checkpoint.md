# Blog Post from Kafle Krishna


I have explained and demostrated the use case in following blog. Please do visit the blog for details and give feedback if you have any.
https://kaflekrishna.com.np/blog-detail/enhanced-vegetation-index-evi-sentinel-2-image-google-earth-engine/

## Enhanced Vegetation Index (EVI) from Sentinel-2 image on Google Earth Engine (GEE):

The enhanced vegetation index (EVI) is an 'optimal' vegetation index that decouples the canopy background signal and reduces atmospheric impacts to improve the vegetation signal with greater sensitivity in high biomass regions and improved vegetation monitoring.

EVI includes an "L" value for canopy background, "C" values for air resistance coefficients, and blue band (B) values. In most cases, these improvements allow for index calculation as a ratio of the R and NIR values while minimizing background noise, ambient noise, and saturation.

EVI = G * ((NIR - R) / (NIR + C1 * R – C2 * B + L))

### Post follows:
Google Earth Engine with python Api.

#### Expected Output of code is as follows:

<br>

<img src = 'EVI_cover.png' align="center">

<img src = 'EVI.png' align="center">