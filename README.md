# 🧠 Image Reconstruction from fMRI Data – COL786 Project

This repository contains the implementation of an **image reconstruction pipeline from fMRI data**, developed as part of the **COL786: Advanced Brain Imaging and Analysis** course project at IIT Delhi.

The project explores the interface between **neuroscience and deep learning**, specifically aiming to reconstruct **visual stimuli** from raw brain activation patterns using machine learning models.

## 📁 Repository Structure
📦 brain-image-reconstruction/
┣ 📄 Image_Reconstruction_Test01.ipynb
┗ 📄 README.md


## 📓 Notebook Overview

The Jupyter notebook `Image_Reconstruction_Test01.ipynb` contains:

- 📚 **Data loading and preprocessing** of fMRI voxel activation data
- 🧠 **Model architecture** (autoencoder / CNN-based decoder - GAN-based framework)
- 🏋️‍♂️ **Training** using paired stimulus-image and fMRI response
- 🖼️ **Evaluation and visualization** of reconstructed images
- 📊 **Metrics** for reconstruction quality (e.g., MSE, SSIM)

> 💡 The notebook is designed for clarity and modularity to help understand each step of the reconstruction pipeline.

## 📦 Requirements

To run the notebook, ensure the following Python libraries are installed:

```bash
pip install numpy pandas matplotlib scikit-learn torch torchvision nibabel opencv-python seaborn
```
 
## Applications
Reconstructing visual experiences from brain scans

Brain-computer interface (BCI) research

Neural decoding and consciousness studies
