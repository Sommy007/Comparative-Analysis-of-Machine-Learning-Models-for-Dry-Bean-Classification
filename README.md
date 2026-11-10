# Project Overview

This project aims to develop and evaluate supervised machine learning classification algorithms to distinguish seven varieties of dry beans based on their morphological and geometric characteristics. The dataset, obtained from the UCI Machine Learning Repository, consists of images of dry bean grains captured using a high-resolution camera. A computer vision system was employed to process the images through segmentation and feature extraction, generating numerical measurements that describe the physical dimensions, shape, and structure of individual bean grains.

The dataset consists of 13,611 observations and 17 variables (16 predictor variables and 1 target variable), with no missing values. The predictor variables represent morphological and geometric characteristics of the bean grains, including Area, Perimeter, MajorAxisLength, MinorAxisLength, AspectRatio, Eccentricity, ConvexArea, EquivDiameter, Extent, Solidity, Roundness, Compactness, ShapeFactor1, ShapeFactor2, ShapeFactor3, and ShapeFactor4. The target variable, Class, categorizes the bean grains into seven varieties: Seker, Barbunya, Bombay, Cali, Dermosan, Horoz, and Sira.

The primary objective of this project is to compare the performance of different machine learning classification algorithms and identify the model that most accurately distinguishes among the seven dry bean varieties based on their morphological and geometric characteristics. Accurate classification of dry bean varieties can support automated seed identification, improve sorting efficiency, ensure product uniformity, and reduce reliance on manual inspection. This study also demonstrates the application of data analytics and machine learning techniques in agricultural classification, automated quality assessment, and precision agriculture.


## Project Goal
This project aims to use supervised machine learning (multiclass classification) to identify and predict the variety of dry bean grains among seven classes (Seker, Barbunya, Bombay, Cali, Dermosan, Horoz, and Sira) using 16 morphological and geometric features extracted from bean images.

## Variables  
Target(Output): Class  
Features(Input): Area (pixels), Perimeter, MajorAxisLength, MinorAxisLength, AspectRatio, Eccentricity, ConvexArea, EquivDiameter, Extent, Solidity, Roundness, Compactness, ShapeFactor1, ShapeFactor2, ShapeFactor3, ShapeFactor4.   

## Data Source  
Dataset Name:  Dry Bean Dataset   
Source: UCI Machine Learning Repository   
Authors: M. Koklu and I. A. Özkan   
Year: 2020   
Publication: Multiclass classification of dry beans using computer vision and machine learning techniques  
Journal: Computers and Electronics in Agriculture   
DOI / Reference: https://doi.org/10.1016/j.compag.2020.105507   

## Methodology
The project follows a structured machine learning workflow:  
- Data Overview/Collection  
- Data Preprocessing   
- Exploratory Data Analysis (EDA)    
- Feature Engineering    
- Feature Analysis and Selection   
- Model Selection   
- Hyperparameter Tuning   
- Model Evaluation








## Tech Stack   
Programming Language: Python   
Libraries: NumPy, Pandas, Matplotlib, Seaborn  
Machine Learning packages/tools: Scikit-Learn, PyTorch  
Model Used: Logistic Regression, Support Vector Classifier (SVC), XGBoost, Feedforward Neural Network (FNN)/ Multilayer Perceptrons (MLPs)  

