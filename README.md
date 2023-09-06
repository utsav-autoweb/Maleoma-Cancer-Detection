# Melanoma Cancer Detection
> Melanoma Cancer Detection Using Convulational Neural Networks


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)




## General Information

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion



## Conclusions
- Initial Model with 4 Convolution layer 2DMaxPool and a dense Layer of 128 Overfitted as we didn't use any Regularization
- Adding Dropouts of 0.2 helped fix the overfitting
- The score was still low as the Traing Data had huge imbalance
- We used argumentation to create 500 more images for each class. 
- After the Trainig data was balanced, we created another model with 3 Convolution Layers with 2DMax Pool, Dropouts and dense layer
- We got 94.75% accuracy in training and 82.55% accuracy in nValidatio data




## Contact
Created by [@utsav-autoweb] - feel free to contact me!

