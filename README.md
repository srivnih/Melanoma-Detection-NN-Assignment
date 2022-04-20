
# Melanoma Detection
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Information](#general-information)
* [Steps followed](#steps-followed)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

## General Information
To detect Melanoma from the set of images which have the below diseases:-
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Steps followed
1. Data Reading/Data Understanding 
2. Dataset Creation
3. Dataset visualisation
4. Model Building & Training 
5. Model Building & training on the augmented data
6. Class distribution
7. Handling class imbalances
8. Model Building & training on the rectified class imbalance data 

## Conclusions
From the CNN model we can conclude the below :-
1. The Training and Validation accuracy on the training data improved significantly after using Augmentor and Treating Class imbalance
2. Final Model does not show overfitting or underfitting
3. Training & Validation accuracy of the final model is 95.27% and 88.12% which is quite good
4. Training and validation loss has decreased with the increase in the number of epochs
5. We can increase the number of epochs to further increase the accuracy of the model

## Technologies Used
- Python 3.8.8
- Jupyter Notebook 6.3.0
- Git 2.33.1.windows.1
- Tensorflow
- Keras
- Pandas
- Augmentor

## Contact
Created by [@srivnih] - feel free to contact me!