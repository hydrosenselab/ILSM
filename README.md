## High resolution landslide susceptibility mapping using ensemble machine learning and geospatial big data


![graphical abstract drawio](https://github.com/der-knight/ILSM/blob/main/Images/graphical%20abstract.jpg)
This is the repository of the India Landslide Susceptibility Map.  
The Input Data Prep includes code for data preparation after data is acquired. 
The models file includes models loading and ensemble generation, and the output_prep includes code for data postprocessing and data vizualization  
The data for the model used can be obtained from source  
## The Raw Tiff files can be obtained from:
https://zenodo.org/doi/10.5281/zenodo.10085271
## The Google Earth Engine code for loading ILSM
````
var ILSM_class= ee.Image("projects/ee-nirdeshsharmanith1/assets/ILSM")  
var ILSM_probability=ee.Image("projects/ee-nirdeshsharmanith1/assets/ILSM_probability")  
````
## The Google Earth Engine code for visualizing ILSM
https://hydrosense.users.earthengine.app/view/ilsm
