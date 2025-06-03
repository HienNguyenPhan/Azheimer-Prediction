# Azheimer-Prediction
This project focuses on predicting whether a subject is diagnosed with **Alzheimer's Disease (AD)** based on 3D functional MRI (fMRI) scans. The pipeline includes data preprocessing, augmentation, and metadata handling for training deep learning models.

# Project structure
├── data_augmented/ # Folder containing augmented fMRI scans (.nii/.nii.gz)  
├── final_nii_metadata.csv # Original metadata file with labels and subject IDs  
├── labels_augmented.csv # Output CSV containing metadata for augmented images  
├── Full project.ipynb # Full notebook of the project  
├── results/ # Folder containing plots and results  
├── best_model.pt/ # Checkpoint of the model with the lowest validation loss  
└── README.md

# How to use
Run the Full project notebook. 
