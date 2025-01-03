# Smart Warehouse System

Frozen products are available and consumed in almost every corner of the world. There are
several advantages of frozen products like increased shelf life, cheaper than the conventional
food etc. All these products are stored in inventory operating at temperatures beyond -18C and sorting this inventory might be a tough task when humans are involved. Conventional freezers can’t be kept open for long time as it runs on CO2 and counting the boxes for daily inventorying can be considered inhumane. So, we have to find ways to automate the process
of counting the boxes where human reach is usually not considerable.

In this project, a smart warehouse counting system has been implemented using Artificial
intelligence, IoT and cloud where the counting of boxes can be done remotely and slightest human intervention.

## Dataset

This dataset was exported via roboflow.ai.

It includes 340 images.
Box are annotated in YOLO v3 Darknet format.

The following pre-processing was applied to each image:

Auto-orientation of pixel data (with EXIF-orientation stripping)
Resize to 416x416 (Stretch)
The following augmentation was applied to create 3 versions of each source image:

50% probability of horizontal flip
50% probability of vertical flip
Random rotation of between -10 and +10 degrees

Link for dataset: https://www.kaggle.com/datasets/sampreetvaidya/warehouse-box-count

## Prediction results

!(img/result-1)
