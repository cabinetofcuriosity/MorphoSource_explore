# README.md: MorphoSource_explore

### About

The purpose of this project is to explore and document methods on how to manipulate and extract 3D data. The primary data source we will be using comes from MorphoSource which provides free and accessible datasets [here](https://www.morphosource.org).

This repository will store all the notebooks, datasets, images, and other resources used in the exploration. Because there isn't a lot of documentation on how to work with these types of data, the goal is to discover and provide repoducible methods for 3D data manipulation and image-processing to the public. 


### Notebooks

The notebooks will serve to mainly document my progress, findings, analysis, and other resources throughout the project. Currently, the notebooks are as follows: 

1. Accessing_MorphoSource.ipynb : An introduction to MorphoSource, how to navigate the website and access the 3D data files

2. Exploring_MorphoSource.ipynb : Brief analysis/exploration of quantifiable data describing the 3D image data, and questions to think about 

3. SciKit_Image_MorphoSource.ipynb : Example of scikit-image image segmentation on 3D data image


### Projected Objectives

1. Learn how to re-construct 2d stack scans (or 2d image) into a rendered 3D image (similar to FIJI) in scikit-image
2. Reconstruct 2d stack scans into 3d image using [Automorpho](https://github.com/HullLab/AutoMorph) 
3. Understand 3d morphometrics and consider ways to extract characteristic data from 3d image data
