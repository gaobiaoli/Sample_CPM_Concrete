# Semantic Segmentation-Based Framework for Concrete Pouring Progress Monitoring

This repository contains sample code based on the paper **"Semantic segmentation-based framework for concrete pouring progress monitoring by using multiple surveillance cameras"** (DOI:https://doi.org/10.1016/j.dibe.2023.100283). The code implements the approach described in the paper to monitor the progress of concrete pouring using semantic segmentation techniques.

## Project Overview

The framework leverages semantic segmentation to monitor the progress of construction activities, particularly focusing on concrete pouring, by utilizing multiple surveillance cameras installed on-site. The approach helps improve accuracy in real-time construction monitoring and decision-making.

## Core Dependencies

- **MMSegmentation**: The core segmentation library used in this project for training and inference.
  - Repository: [MMSegmentation](https://github.com/open-mmlab/mmsegmentation)
  
- **vUtils**: A custom toolkit developed by myself for digital twins
  - Repository: [vUtils](https://github.com/gaobiaoli/vUtils.git)
  ```bash
  pip install git+https://github.com/gaobiaoli/vUtils.git
  ```

## Model Weights

Get weight to $PATH/model from https://drive.google.com/uc?id=1Pf-izHaMJaM6euyAyJ-Q4h5srVuweOpy




