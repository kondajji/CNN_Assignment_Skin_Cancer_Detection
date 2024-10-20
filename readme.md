# Project Name
> To build a multiclass classification model using a custom convolutional neural network in TensorFlow. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer 
  deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were  sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.



## Conclusions
## **Overall Summary**

Totally 3 models were built. The thid model gave best Training and Validation Accuarcy. **Data Augmentation was performed to handle Class Imablance**. Model complexity was reduced and hyperparameter tuning (dropout layers) were added to control overfitting of model.

**Final CNN Model consists of:**
1. Three convolutional layers with increasing filters (32, 64, 128).
2. Max-pooling layers after each convolutional layer to reduce the spatial dimensions.
3. Dropout layers to prevent overfitting.
4. Dense layers to perform classification with the final output using a softmax activation for multi-class classification.




## Technologies Used
- library -Tensorflow
- library - Keras
- library - Matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project is prepared as Part of Assignment from UPgrad-IITB Program.
- References if any...
- https://www.kaggle.com/code/fanconic/cnn-for-skin-cancer-detection
- https://neptune.ai/blog/data-augmentation-in-python
- https://medium.com/techiepedia/binary-image-classifier-cnn-using-tensorflow-a3f5d6746697


## Contact
Created by @kondajji


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->