# SCF-YOLO

## HelmetDet: 
This data set is a safety hat open data set. In this project, there are a total of 3437 images in the data set, and 2114 of them are extracted from the power industry safety hat data set, with a total of 9619 label samples. Among them, the number of wearing helmet labels is 8550, and the number of not wearing helmet labels is 1069. Take COCO object definition, a general dataset in the field of object detection, as an example, The distribution of large, medium and small targets in this dataset is 7122, 5861 and 3304.

## Elec-hat: 
In order to evaluate the proposed method, we created a new dataset of helmets for electrical construction workers. We refer to the dataset for images with and without helmets. To enrich the dataset, we also collected images of power construction scenes with and without helmets on the Internet. We named it Elec-hat. the total number of helmet images is 7000, containing two category labels (with and without helmet), and the images collected in this dataset are from real environments with a high number of power construction workers wearing helmets, which overlap and obscure each other severely. 

## SHWD: 
A publicly available dataset for helmet wear detection is provided.It includes a total of 7581 images with 9044 human helmet wearers (positive) and 111514 normal head objects (unworn or negative).

<img src=".\VOC2007\jpg\000048.jpg" width="300px"><img src=".\VOC2007\jpg\000009.jpg" width="300px">
<img src=".\VOC2007\jpg\000019.jpg" width="300px"><img src=".\VOC2007\jpg\000025.jpg" width="300px">
<img src=".\VOC2007\jpg\000030.jpg" width="300px"><img src=".\VOC2007\jpg\000037.jpg" width="300px">


The model part of the module code is shown in the file model.py. The dataset is shown in the folder VOC2007. Since some of our dataset comes from the subject project, we will only disclose part of the data at the moment, and the rest of the dataset will be disclosed when the engineering project is completed!
