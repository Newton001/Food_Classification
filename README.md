# Classifying meal images into major food categories

## Overview

Adhering to a healthy and balanced diet is essential for reducing the risk of non-communicable diseases.
This project focuses on creating an automatic
dietary assessment system using Convolutional Neural Networks (CNNs) and advanced machine learning techniques.

## Table of Contents

- [Data](#data)
- [Experiment](#experiment)
- [Prerequisites](#Prerequisites)
- [Usage](#usage)
- [Installation](#Installation)


## Data

The dataset, named Food-11, consists of 16,643 food images categorized into 11 major food types. 
The dataset is divided into training, validation, and evaluation subsets, providing a comprehensive
set of images for model development and evaluation.

## Experiment

The core experiment involves training a CNN for food classification. Various pretrained CNN architectures
(ResNet, Inception, VGGNet, EfficientNetB0) and custom models are explored. Class activation maps (CAM) and gradient
class activation maps (Grad-CAM) are generated to visualize where the CNN is "looking."

## Prerequisites

List the software and libraries required to run your Jupyter Notebook. Include versions if necessary.

- Python (version 3.11)
- Jupyter Notebook
- TensorFlow (version 2.14.0)
- 
# Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yvesunibe/DDM_Project.git

2. cd DDM_Project

3. Install the requirements as below
4. Open and run Jupyter Notebooks in the notebooks for detailed experiments and analyses.

## Installation


```bash
pip install -r requirements.txt
