Melanoma Detection on the International Skin Imaging Collaboration (ISIC) Dataset

This project aims to create a custom Convolutional Neural Network (CNN) model for detecting melanoma using the International Skin Imaging Collaboration (ISIC) dataset. By leveraging deep learning techniques, the goal is to provide a tool that assists dermatologists in identifying potential cases of melanoma, ultimately improving early detection and patient outcomes.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
This project aims to create a custom Convolutional Neural Network (CNN) model for detecting melanoma using the International Skin Imaging Collaboration (ISIC) dataset. By leveraging deep learning techniques, the goal is to provide a tool that assists dermatologists in identifying potential cases of melanoma, ultimately improving early detection and patient outcomes.

Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Conclusions
- The model overfits if trained on the dataset without making any changes
- using techniques like data augmenting (changing the picture orientation for example) helps control overfitting
- There is class imbalance that is impacting the accuracy of the model. Initial training shows more or less 50 percent accuracy across all epochs showing bias in prediction due to class imbalance.
- After taking care of class imbalance using techniques like data augmenting, there is still underfitting which needs to be analysed and improved. One of the challenges faced is to train the model locally as it's taking time to train.

## Technologies Used
Python version 3.8
TensorFlow version 2.13
NumPy version 1.22.0
Matplotlib version 3.3.4
Pandas version 1.2.4
Pillow (PIL) version 8.2.0


## Acknowledgements
Give credit here.
- This project was inspired by upGrad.


## Contact
Created by [github.com/ranju1729] - feel free to contact me!

