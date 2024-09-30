# Enhancing Alzheimer’s Detection via Advanced MRI Analysis

## Overview

This project focuses on leveraging advanced image processing and deep learning techniques to classify the progression of Alzheimer's Disease (AD) using axial MRI brain scans. By analyzing the size of brain ventricles in MRI images, the project aims to assess the severity of Alzheimer's in patients.

Early detection of Alzheimer's Disease through MRI analysis can help improve treatment outcomes. Using a deep learning model, this project classifies MRI scans into varying levels of dementia severity, providing a useful tool for healthcare professionals.

## Scope

### In-Scope
- **Alzheimer’s Disease Progression Assessment**: The primary goal is to assess the progression of Alzheimer's disease using **axial MRI brain scans**.
- **Support for Varying Resolutions**: The model supports MRI images of various resolutions.
- **Ventricle Size Classification**: The classification of Alzheimer's disease severity is based on the size of the brain ventricles, which is one of the critical indicators of neurodegeneration in Alzheimer’s patients.

### Out-of-Scope
- **Other MRI Views**: This project focuses solely on **axial views** of MRI scans. Coronal, sagittal, oblique, and other views are excluded from the scope of analysis.
- **Genetic Data Analysis**: The project does not include genetic information acquisition or analysis for assessing Alzheimer’s severity.

## Assumptions

- The MRI scans are assumed to be in the **axial view**.
- MRI images used in the analysis are sourced from publicly available datasets.

## Datasets

This project utilizes MRI data from the following dataset:

- **[OASIS Dataset from Kaggle](https://www.kaggle.com/datasets/ninadaithal/imagesoasis/data)**: The Open Access Series of Imaging Studies (OASIS) is a publicly available neuroimaging dataset. It provides MRI scans across a wide range of demographics and cognitive states. The dataset includes images of varying resolutions, making it suitable for the project’s scope of supporting diverse MRI inputs.

## Project Structure

- **`DeepModelFinal.ipynb`**: Jupyter notebook that contains the code for preprocessing MRI images, training the model, and visualizing results.
- **`/data`**: Directory where the MRI scan data should be stored. The directory structure should follow the organization of the OASIS dataset.

## Setup

### Requirements

- **Python 3.x**
- **Libraries**:
  - `matplotlib`
  - `Pillow`
  - `tensorflow` or `keras` (for deep learning)
  - `numpy`
  - `sklearn` (for metrics and preprocessing)
  - `scipy`
