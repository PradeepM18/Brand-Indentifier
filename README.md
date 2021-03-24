# Brand-Indentifier


## Problem Statement

The problem would be on object detection, where training images are just instances of the object.

This is unlike normal object detection where train and test images are scenes with objects inside them are tagged with a bounding box. You can download the dataset from here -> https://github.com/gulvarol/grocerydataset.

Dataset description is given in detail there, I'm describing below your task requirements.

There are 10 classes (cigarette brand) and we want you to detect the brands in the shop images (ie localize the boxes and classify the brand)

Trainset -> './BrandImages'

Testset -> './ShelfImages'

Testset Annotations -> './BrandImagesFromShelves'

Accuracy Metric -> Standard object detection metric, mAP. (Please include visualizations of predictions)

## Approaches

The approach I have used is to detect objects in image throug annotation and classify it and predict the results.

To do this I have used Deep Learning algorithms like **VGG16, Resnets and Inception** based models.

To improve the accuracy I have also used various data preprocessing and Transfer Learning methods and ensemble methods.

** I have made the python notebook highly descriptive, so please go through it to understand it clearly**


## Results


| Models | Accuracy | 
| --- | --- |
| VGG-16 Plain form | 12 |
| VGG-16 Data Augumentation +Transfer Learning| 62|
| VGG-16 Data Augumentation +Transfer Learning , Introducing Realworld Images|98|
| Resnet Data Augumentation +Transfer Learning , Introducing Realworld Images|99|
| Inception V3 Data Augumentation +Transfer Learning , Introducing Realworld Images|99|
| Stacking |99|


## Visualizing Results


![Reslts](https://github.com/PradeepM18/Brand-Indentifier-/blob/main/Results.PNG)
