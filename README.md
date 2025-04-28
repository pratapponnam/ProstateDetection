ProstateX Challenge - Lesion Analysis:

This repository contains three approaches for prostate lesion analysis:

2D CNN classification
3D CNN classification
3D MONAI Attention UNet segmentation

Folder Structure:

CNN_2D.ipynb — 2D CNN model
CNN_3D.ipynb — 3D CNN model
MONAI_3d.ipynb — 3D MONAI Attention UNet model
data_preprocess_week_1.ipynb and DataPreprocessing_3D_CNN.ipynb — Data preprocessing notebooks
EDA.ipynb — Exploratory Data Analysis

How to Run

1. 2D CNN
   
Open and run CNN_2D.ipynb.
Important: Change the dataset path at the top of the notebook to where your dataset is located.

2. 3D CNN
   
First, run the preprocessing notebooks:
Run data_preprocess_week_1.ipynb and/or DataPreprocessing_3D_CNN.ipynb to generate the processed data.
Then, run CNN_3D.ipynb for model training and evaluation.
Important: Change the dataset/output folder paths in the preprocessing and model notebooks as needed.

3. MONAI 3D Segmentation
   
Open and run MONAI_3d.ipynb.
Important: Like the 2D CNN, only the dataset path needs to be updated at the top of the notebook.

Requirements
Python 3.8+

Jupyter Notebook

Key libraries:
torch
monai
numpy
pandas
matplotlib
SimpleITK
pydicom
scikit-learn

Tip: Install all dependencies using pip install -r requirements.txt if you have one, or manually install missing libraries.

Notes
This project assumes the ProstateX dataset is already downloaded and locally available.

Make sure the directory structure matches what the notebooks expect, or update the paths accordingly.
