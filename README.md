## Overview
Despite the ongoing research and practical interests, car make and model analysis only attracts few attentions in the computer vision community. We believe the lack of high quality datasets greatly limits the exploration of the community in this domain. To this end, we collected and organized a large-scale and comprehensive image database called VMMRdb, where each image is labeled with the corresponding make, model and production year of the vehicle.	

## Description
The Vehicle Make and Model Recognition dataset (VMMRdb) is large in scale and diversity, containing 9,170 classes consisting of 291,752 images, covering models manufactured between 1950 and 2016. VMMRdb dataset contains images that were taken by different users, different imaging devices, and multiple view angles, ensuring a wide range of variations to account for various scenarios that could be encountered in a real-life scenario. The cars are not well aligned, and some images contain irrelevant background. The data was gathered by crawling web pages related to vehicle sales on craigslist.com, including 712 areas covering all 412 sub-domains corresponding to US metro areas. Our dataset can be used as a baseline for training a robust model in several real-life scenarios. 	
<p align="center"><img align="center" src="http://vmmrdb.cecsresearch.org/imgs/dbHeatmap.png" alt="VMMRdb data distribution" width="600px"></p>
<p align="center">The distribution of images in different classes of the dataset. Each circle is associated with a class, and its size represents the number of images in the class. The classes with labels are the ones including more than 100 images.</p>

## Download
VMMRdb can be downloaded [here](http://vmmrdb.cecsresearch.org/).

Each image is labeled with the corresponding make, model and production year of the vehicle.

## Citation
If you use this dataset, please cite the following paper:
```
A Large and Diverse Dataset for Improved Vehicle Make and Model Recognition
F. Tafazzoli, K. Nishiyama and H. Frigui
In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR) Workshops 2017. 
```
