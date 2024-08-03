# EigenHands

## Overview
This Jupyter Notebook explores the application of Principal Component Analysis (PCA) on a dataset of hand images. The main focus is on reducing the dimensionality of the dataset while trying to retain as much information as possible using the eigenhand technique.

## Features
  - **Data Preprocessing**: Includes normalization and reshaping of image data.
  - **PCA Implementation**: Eigenvalue and eigenvector computation from the covariance matrix of the dataset.
  - **Dimensionality Reduction**: Projecting the high-dimensional data onto a lower-dimensional space using principal components.
  - **Image Reconstruction**: Reconstructing images from the reduced dimensionality to visualize loss due to compression.

## Usage
  - Ensure all prerequisites are installed.
  - Run the cells sequentially to observe preprocessing, PCA, and the effects of dimensionality reduction.

## Prerequisites
  - Python 3.6 or above
  - Jupyter Notebook or JupyterLab
  - Libraries: numpy, matplotlib

## Input
The input to this notebook is a dataset containing images of hands, which are not provided in the notebook but are loaded through a hypothetical path.

## Output
  - Plots of original vs. reconstructed images to demonstrate the effect of PCA.
  - Printed eigenvalues and percentage of variance explained by principal components.

## Notes
- Ensure the dataset path is correctly set to where the hand images dataset is stored.
- The notebook assumes some familiarity with PCA and eigen decomposition.