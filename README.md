# 'Distracted Driver Detection using Machine Learning Techniques'

## Overview

### Introduction
Most people tend to follow safety guidelines while driving, yet there is a continuous increase in car accidents every year leading to loss of lives. One major factor that contributes towards the accidents is the driver distractions while driving. Current distracted driving statistics show that 80% of all car accidents are caused by the driver being  distracted in some way. Thus, to reduce the number of car accidents, being able to identify distracted driving is a major task.

### Problem Description
The goal of this project is to detect if the car driver is driving safe or performing any activity that might result in a accident or any harm to others. The dataset contains various driver images, each taken in a car with a driver performing some activity in the car. We are determined to classify the likelihood of what the driver is doing in each image. We aim to use various Machine Learning techniques to classify driver’s activities and identify a model that yields the highest accuracy. The model is trained on image data that are the images of driver's actions in the car. This is a multi-class classification problem, with a total of 10 classes including a class of ‘safe driving’. The image below gives the 10 classes:

[`Source`]

Below are the 10 classes to classify:

c0: safe driving

c1: texting - right

c2: talking on the phone - right

c3: texting - left

c4: talking on the phone - left

c5: operating the radio

c6: drinking

c7: reaching behind

c8: hair and makeup

c9: talking to passenger

### Dataset
Our [`Dataset`] is from a 2016 Kaggle competition with a huge collection of 22,500 640x480RGB images.

## mplementation

### Pre-processing
We pre-processed these  images by resizing them to a lower size and extract each image’s features by converting it to a column vector which will contain the RGB values stacked one after the other for a single example. We will then combine the vectors for each of the data instances and create a matrix as the input data to our models.Pre-processing of the data will be a challenge because we will have to figure an optimum value to resize the image.

### ML Algorithms


## Applications

Our models are applicable to the following applications and many more
1.  If installed in a car, it can alarm/warn if the driver is distracted.
2.  In semi-autonomous vehicles, the vehicle can take control if the driver is distracted.
3.  Government can use to enforce laws on safe & distraction free driving.
4.  Auto Insurance companies can use these models in re-writing auto policies.


[`Source`]: http://cs229.stanford.edu/proj2019spr/report/24.pdf
[`Dataset`]: https://www.kaggle.com/c/state-farm-distracted-driver-detection/data
