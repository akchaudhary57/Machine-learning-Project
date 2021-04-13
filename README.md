# Facial Emotion detection

### Introduction

This notebook is for the major project submission on the Facial emotion dection task. It contains the following sections:

1. Conventional ML approach
2. Deep learning approach


### Conventional ML Model

I will apply PCA (Principal Component analysis) and finally, SVM to predict the facial emotion detection as this model is well known for multi-label classfication. We will also try other classification model and check the model accuracy. The reason for choosing PCA is it assist in reducing dimension and preserve most important features, which results in better accuracy on the data.

### Deep learning approach

I will be using Convolutional Neural Network to classify facial emotions. The CNN model is good for extracting the features of the images and is widely used for image classification.


### Discussion of Model Performance and Implementation

Comparing the final conventional ML and deep learning models, the deep learning performed better by 10% on the public test set. The deep learning model ranked #15 out of 8 submissions on the public test set, with the top-performing system having 71.39% accuracy, and a majority class baseline having 65% to 69% accuracy. In the private dataset, I ranked #15 with slight increase of 2.5% in accuracy. The validation and public dataset had approximately similar accuray level.
