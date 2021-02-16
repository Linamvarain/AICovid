# AICovid 

ResNet-18 model is used and trained on a COVID-19 Radiography dataset. 
The objective is to create an image classification model that can predict Chest X-Ray scans that belong to one of the three classes with a reasonably high accuracy.


# Installation
Please refer to install.md for installation.

# Dataset
AICovid uses the dataset from "COVID-19 Radiography Dataset" on Kaggle. It contains chest X-ray images for COVID-19 positive cases along with Normal and Viral Pneumonia images. In the adopted realease there are 1200 COVID-19 positive images, 1341 normal images and 1345 viral pneuomonia images. 


***Formats

All the images are in Portable Network Graphics (PNG) file format and resolution are 1024 * 1024 pixels and 256 * 256 pixels, which will be converted to 224 * 224 required by the Convolutional Neural Networks (CNNs).

