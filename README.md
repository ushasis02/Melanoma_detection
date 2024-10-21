# Melanoma_detection
Melanoma detection NN

# Project Name
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* .ipynb notebook with the model and the analysis
* The code is primarily written in Python using Keras and Tensorflow
* The best model was obtained with a learning rate annealer wherein the accuracy was 63%

## General Information
- What is the background of your project?
   There are 9 classes of images for detection of melanoma. The objective is to identify the 9 classes from the 2300+ images given 
- What is the business probem that your project is trying to solve?
   It will help dermatologists to get an idea of the type of skin problem by diving it into 9 classes based on the image
- What is the dataset that is being used?
   The International skin Imaging collaboration (ISIC) has provided the images for skin cancer detection

## Conclusions
- Standard CNN causes underfitting 
- Using a learning rate annealer causes the model to perform better at 63% but has some overfitting (validation accuracy:39%)
- Using augmentation to boost the less represented class underfits the model
- Best training accuracy obtained is 63% with some overfitting

## Technologies Used
- Tensorflow 2.12.0
- Keras

## Acknowledgements
Project was developed and run on Google Colab
