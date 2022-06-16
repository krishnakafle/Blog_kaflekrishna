# Blog Post from Kafle Krishna

I have explained and demostrated the use case in following blog. Please do visit the blog for details and give feedback if you have any.
https://kaflekrishna.com.np/blog-detail/extraction-raster-values-point-samples-google-earth-engine-gee/

## Extraction of raster values from point samples on Google Earth Engine (GEE)

Extracts the cell values of a raster-based on a set of point features and records the values in the attribute table of an output feature class.
In this tutorial, We plan to extract the raster cell values from the set of point features on Google Earth Engine (GEE) with python API. Before we dive into the working steps, I will explain the general idea of how this concept can be implemented. 
The process of raster value extraction can be implemented in two ways, 

Directly extracting the raster values by overlaying raster with point data. Raster value which perfectly overlays with the point is taken.
Buffer (circle, square) around the point is created, and raster statistics (mean) are obtained. This mean is taken as the raster value for points. Refer this: 
https://www.neonscience.org/resources/learning-hub/tutorials/extract-values-rasters-r



#### Expected Output of code is as follows:
<br>

<img src = 'table_data.png' class="center">

<img src = 'plot_EVI.png' class="center">

<img src = 'plot_NDVI.png' class="center">