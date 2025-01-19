# Skin Cancer Classification System

This repository contains the code for a Skin Cancer Classification System that leverages advanced machine learning techniques to classify 7 different types of skin cancer. The system achieves a best accuracy rate of 84%.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Models](#models)
- [Results](#results)

## Overview
This project aims to improve the accuracy of skin cancer detection through the combination of custom Convolutional Neural Networks (CNNs) with DenseNet169 and ResNet50 architectures. Additionally, it incorporates the Dull Razor technique to remove hair artifacts and U-Net for the segmentation of skin lesions.

## Features
- Classification of 7 different skin cancer types
- Hair artifact removal using the Dull Razor technique
- Skin lesion segmentation using U-Net
- High accuracy with a success rate of 84%

## Technologies
The project utilizes the following technologies and algorithms:
- Neural Networks
- DenseNet169
- ResNet50
- Dull Razor Algorithm
- U-Net Algorithm

## Installation
To get a local copy up and running, follow these simple steps:

1. Clone the repo
    ```sh
    git clone [https://github.com/drohan0717/Skin-Cancer-Detection-System.git]
    ```

## Usage
Instructions on how to use the project:

1. Prepare the dataset and place it in the directory, i have not included the dataset because of space constraints.
2. NoteBooks of all the models used is provided, there are 4 files for each model(Custom CNN, densenet169, resnet50 and ensemble) which correspond to no sampling, oversampling(using smote), oversampling(using random oversampler) and undersampling.

## Dataset
The project uses the ham 10000 dataset that includes 10015 images that correspond to 7 different types of skin lesions(inluding both benign and malignant samples). Please download the dataset from (https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) and preprocess it and store the images in form of csv files and place it in the directory.

## Models
The project utilizes custom CNNs, DenseNet169, and ResNet50 for classification tasks. The U-Net model is used for segmentation, and the Dull Razor algorithm is applied for hair artifact removal.

## Results
The system achieves a best accoracy of 84% accuracy rate in classifying 7 different types of skin cancer. 
