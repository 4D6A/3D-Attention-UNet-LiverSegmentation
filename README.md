# 3D Attention U-Net for Liver Tumor Segmentation in CT Scans
Project Title: "3D Attention U-Net for Liver Tumor Segmentation in CT Scans" 
Problem: Segment malignant liver tumors with irregular boundaries in low-contrast CT scans. 
Dataset: Medical Segmentation Decathlon (Task03_Liver): http://medicaldecathlon.com 
Model: 3D U-Net with gated attention mechanisms in TensorFlow.

## 🧠 Project Overview
This project implements a 3D U-Net architecture enhanced with gated attention mechanisms to segment malignant liver tumors from low-contrast CT scans. It is built using TensorFlow and trained on the [Medical Segmentation Decathlon Task03_Liver dataset](http://medicaldecathlon.com).

## 🎯 Problem Statement
Accurate segmentation of liver tumors with irregular boundaries in low-contrast CT scans is a challenging task. This model aims to improve segmentation performance using attention mechanisms that focus on relevant spatial features.

## 📂 Dataset
- **Source**: Medical Segmentation Decathlon (Task03_Liver)
- **Format**: NIfTI (.nii.gz)
- **Preprocessing**: Resampling, normalization, and patch extraction

## 🏗️ Model Architecture
- 3D U-Net backbone
- Gated attention blocks in skip connections
- Residual connections for deep feature learning

## 🛠️ Installation
```bash
git clone https://github.com/your-username/3D-Attention-UNet-LiverSegmentation.git
cd 3D-Attention-UNet-LiverSegmentation
pip install -r requirements.txt
