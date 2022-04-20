# Melanoma Cancer Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#Technologies-Used)
* [CNN Steps](#Steps-Used)
* [Conclusions](#Conclusions)


## General Information
> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Technologies-Used
- Tensorflow      - Version : 2.5.0
- numpy       - Version : 1.20.1
- pandas      - Version : 1.3.5
- matplotlib  - Version : 3.3.4
- Augmentor

## Steps-Used

- Data Reading - Loading
- Dataset Creation
- Dataset Visualization
- Model 1 Building , Training , Evaluation and Findings -- CNN Model with Dropout layer
- Model 2 Building , Training , Evaluation and Findings -- CNN Model with Augment strategy and Dropout layer
- Model 3 Building , training , Evaluation and Findings - CNN Model with Augmentor to rectify imbalance class data

## Conclusions
-The class rebalance helped in reducing overfititng of the data and thus the loass is beng reduced But it reduced the Acurracy very low
-Initially we tried without the ImageDataGenerator which created data to over fit at high ratio
-Then we introduced dropout and ImageDataGenerator which reduced the over fit
-At last we tried Batch Normalization and Augumentation which really helped in carry forward


## Contact
Created by [@shreyans557]


