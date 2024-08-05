# Melanoma-Detection-Assignment
**Problem statement:** To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We have created 3 CNN models for predictions and their performance are as follows

| Model | Best Train Accuracy | Best Validation Accuracy | Best Test Accuracy |
| --- | --- | --- | --- |
| Base Model | 56.42% | 53.24% | 38.33%
| With Data Augmentation | 52.51% | 53.69% | 35.83%
| With Handled Class Imbalance | 88.85% | 84.26% | 43.33%

We can improve accuracy on test by adding more layers to model.


## Technologies Used
- tensorflow
- keras
- matplotlib
- Augmenter
- pathlib
- glob

## Contact
Created by [@shootingStar10](https://github.com/shootingStar10) - feel free to contact me!
