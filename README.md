# DyT-KAN-HSN: Robust Bi-temporal Tree Change Detection

This is the official PyTorch implementation of the paper:
**"Robust Bi-temporal Tree Change Detection via Hyperbolic Siamese Networks with KAN-Inspired Transformation and Dynamic Tanh Normalization"**
This repository provides the source code and pre-trained model weights for the **DyT-KAN-HSN** framework. The model integrates Dynamic Tanh (DyT) normalization and a lightweight KAN-inspired feature transformation into a Hyperbolic Siamese Network to achieve robust bi-temporal remote sensing change detection.
## Pre-trained Weights
Due to GitHub file size constraints, the pre-trained model weights (`.pth` files) are hosted as release assets. 
You can download the official weights for all three datasets here:
👉**[Download Pre-trained Weights (v1.0.0)](https://github.com/zxinyan51-cell/KAN-Dyt-HSN/releases/tag/v1.0)**
## Environment Setup
```bash
# Create a conda environment
conda create -n dytkan python=3.8
conda activate dytkan
# Install PyTorch (adjust according to your CUDA version)
pip install torch==2.1.2 torchvision==0.16.2
# Install other dependencies
pip install -r requirements.txt
