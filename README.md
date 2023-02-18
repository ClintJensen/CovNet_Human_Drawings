# Neural-Nets for prediction (age, gender, ASQ, etc.) through features extracted from drawings with VGG19 architecture with weights pre-trained on ImageNet
- Original VGG-19 Script Author: Pablo Caceres,  Created: 04/01/19,  Updated: 05/20/19
- Edited and added additional scripts within this fork: Clint Jensen, Updated: 08/15/22
## Description  
Repo containing images of human drawings from children and adults  

In a collection of studies we use the VGG-19 ConvNet architecture with weights trained on ImageNet to extract features from intermediate layers. Such features are used to build and train neural-nets. Predictions from this data include: linear prediction of age, binary classification of gender (male vs female), participants physical dexterity, and historically assessed IQ based on dimensionality reduction.


## Requirements
- Tensorflow 1.13.1  
- Python 3.6  
- Python libraries: Numpy, os, Scipy, matplotlib, Sklearn, Pandas, seaborn, pathlib, rarfile  

## How to use
Two options:  
- Locally: run jupyter notebook
- Cloud: run in google colab  

## Current state
Work in progress  
