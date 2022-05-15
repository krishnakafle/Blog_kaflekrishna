# Blog Post from Kafle Krishna

I have explained and demostrated the use case in following blog. Please do visit the blog for details and give feedback if you have any.
https://kaflekrishna.com.np/blog-detail/calculating-ndvi-sentinel-2-images/

## Calculating NDVI from Sentinel-2 Images

The Normalized Difference Vegetation Index (NDVI) measures the difference between near-infrared (which vegetation strongly reflects) and red light (which vegetation absorbs) to quantify vegetation. NDVI always ranges from -1 to +1. If there are no green leaves, the value is zero. A zero denotes no vegetation, whereas a value close to +1 (0.8-0.9) suggests the highest density of green leaves conceivable. However, the land cover type does not have its specific limit of NDVI values.

The formula for calculating NDVI is as follows:

``` NDVI = (NIR — RED)/(NIR + RED) ```

NIR – reflection in the near-infrared spectrum
RED – reflection in the red range of the spectrum


#### Expected Output of code is as follows:
<br>

<img src = 'ndvi_cover.png' class="center">

<img src = 'ndvi.png' class="center">