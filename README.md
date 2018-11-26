# Melanoma Skin Cancer Detection with Deep Learning

ISIC 2018: Skin Lesion Analysis Towards Melanoma Detection

https://challenge2018.isic-archive.com/task3/

# Summary

This repository provides a starting solution for Task 3 of ISIC-2018 challenge based on Keras/Tensorflow.
The current achieved performance is:
82 % accuracy
64 % mean recall

The project support Resnet50 backbone supported by Keras, and for predicted responses we use a normalized multi-class accuracy metric (balanced across categories). 

### Installation /Previous requirements

No previous installations are needed, because to deploy this project we test the performance of the training model on Google Collaboratory who provides free GPU resources for this propuse. Also we use Python 3.
And the datasets were uploaded to Google Colab from Google Drive. 

### To consideration

The development of the project is divided into two scenarios. In the first, it corresponds to a much more complex scenario using a Deep convolutional neural network Resnet50 for image classification. This model is greatly benefited to visual recognition and also increase / improve the classification / recognition accuracy through residual learning.

In the second scenario, a sequential model was used, accompanied by a greater reduction in the size of the images.
Although each model has its advantages, the results were compared for each scenario and its performance.
Start with the first scenario with the notebook: run_melanoma_detection.ipynb

..and continue with the second scenario:
run_melanoma_detection_ (Second Scenario) .ipynb
