# Melanoma Detection using CNN
> The project's objective is to construct a model using CNN technology that can precisely identify melanoma, a potentially fatal form of cancer if not identified promptly. Melanoma constitutes 75% of all skin cancer fatalities. Developing a solution capable of analyzing images and notifying dermatologists about the existence of melanoma holds the promise of significantly reducing the manual labor required for diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- The data set contains the following diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion

## Conclusions
- The Augmentor library was utilized in the final model to generate additional samples artificially, enabling the creation of a model capable of accurately detecting the specific type of cancer. The validation accuracy of this model was approximately 90%. 
- Additionally, the validation loss for the final model amounted to 0.49.

## Technologies Used
- Keras
- Tensorflow
- Augmentor

## Acknowledgements
- The inspiration for this project originated from a case study presented in the Executive PG Program in Data Science by IIIT Bengaluru.


## Contact
Created by [@rahulkpareek] - feel free to contact me!
