# Mapping Landcover Classification
## Overview
This repository contains an analysis which classifies landcover types to understand distribution and of landcover classes in Southern Santa Barbara County. The analysis uses a decision tree classifier, developed by training data, to classify pixels using a series of conditions based on values in spectral bands. It classifies four land cover types: green vegetation, dry grass or soil, urban, and water. Applying the decision tree to the image creates a map of land cover classes.

Understanding land cover classes has large implications in understanding antropogenic and environmental impacts on changes in environment over time.

## About the Data
**Landsat 5 Thematic Mapper**
-   [Landsat 5](https://www.usgs.gov/landsat-missions/landsat-5)
-   1 scene from September 25, 2007
-   bands: 1, 2, 3, 4, 5, 7
-   Collection 2 surface reflectance product\

**Study area and training data**
-   polygon representing southern Santa Barbara county and polygons representing training sites

The data is too large to be pushed to this repository, so download the data [here](https://drive.google.com/drive/folders/1ON8FbDqcTjg2PKHmNGgyN7odTqpOnXla?usp=sharing) and save it locally into a data folder. The data folder is already added to the .gitignore as 'data/'.
    
## Structure
The structure of the repo is as follows:
> ```
> landcover-classification
> │   README.md
> │   landcover-classification.Rproj
> │  .gitignore
> └───documents
>    │   landcover-classification.html
>    │   landcover-classification.Rmd
> ```

The full analysis is contained in the documents folder in the .Rmd file.
