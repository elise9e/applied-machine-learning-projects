# Project 3 - Applying CNN: Trademark Infringement Detection
### Developed by Elise Eldridge (Collaborator: Brynn Beaman)

## Project Overview
This project utilizes a Convolutional Neural Network (CNN) built in PyTorch to detect unauthorized usage of the officially licensed University of Arkansas Razorback logo on Etsy. The model automates the identification of non-compliant vendors to protect university brand identity and revenue.

## Repository Structure & Deliverables

* **`Group_22_CNN.ipynb`**: The primary Jupyter Notebook containing the full pipeline, including custom PyTorch Dataset development, CNN network architecture layers, training loops, and evaluation visualizations.
* **`Group_22_CNN_FullModel.ph` & `best_model_weights.pt`**: The final trained model architecture and saved optimal weights, achieving the highest validation accuracy during testing.
* **`DASC41103_Project3_ApplyingCNN.pdf`**: The project description and technical guidelines.

> ⚠️ **Note on Dataset Access:** The raw image dataset (`razorback_dataset/` containing custom-curated `.jpeg` samples from Etsy) has been explicitly excluded from this remote repository due to GitHub web upload file size limitations. The complete training logs, input transformations, and final confusion matrices remain fully interactive and visible inside the saved outputs of `Group_22_CNN.ipynb`.