# Cardiac Imaging Analysis using CMRI

## Overview:
This project focuses on analyzing cardiac function, crucial for early disease detection in clinical cardiology. Utilizing cardiac magnetic resonance imaging (CMRI), the goal is to classify images into five diagnostic categories, aiming to enhance early disease identification and prevent complications like heart failure and sudden cardiac arrest.

## Highlights:
- Implemented a Random Forest Classifier with meticulous hyperparameter tuning using Grid Search CV.
- Successfully achieved an accuracy score of 89.71% with the Random Forest model.
- Utilized a voting technique for feature selection, ensuring the construction of a robust feature set and guarding against overfitting.

## Dataset:
- Consists of 150 subjects with CMRI images along with corresponding partial segmentations and metadata.
- Data is partitioned into a training-validation set (100 subjects) and a test set (50 subjects).
