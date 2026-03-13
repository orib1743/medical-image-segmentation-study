# Medical Image Segmentation for Wound Detection

## Overview
This project focused on automated anonymization of medical images and generation of segmentation masks based on human annotations.

## Problem
Medical images contained sensitive patient information that had to be removed before analysis.
Additionally, wound areas had to be segmented using deep learning models trained on annotated data.

## Solution
We built a preprocessing and training pipeline that:
- anonymizes sensitive information
- prepares datasets for training
- trains a deep learning segmentation model
- generates wound masks automatically

## Architecture

Images  
↓  
Anonymization pipeline  
↓  
Dataset preparation  
↓  
Segmentation model training  
↓  
Mask prediction  

## Technologies
- Python
- PyTorch
- OpenCV
- segmentation_models_pytorch

## My Role
- designed the preprocessing pipeline
- implemented the training workflow
- evaluated model performance
