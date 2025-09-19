# 🌊 Water Segmentation using Multispectral and Optical Data

## 📌 Project Overview
This project focuses on *segmenting water bodies* using *multispectral and optical satellite imagery*.  
The goal is to provide a *robust and accurate deep learning solution* for monitoring water resources, flood management, and environmental conservation.  

Accurate segmentation of water bodies is essential for:
- 🌍 Environmental monitoring  
- 💧 Water resource management  
- 🌊 Flood detection and control  

---

## 🗂 Dataset
- Each training/testing example contains *12 spectral bands (channels)*.  
- Labels (Y) are *binary masks* (water = 1, non-water = 0).  
- Image dimensions: *128 × 128 pixels*.  

---

## ⚙ Preprocessing
- *Data Preparation*: Preserve the original resolution & shape for spatial integrity.  
- *Normalization*: Standardize input across different sensors for stable training.  
- *Visualization*: Display each spectral band to analyze data quality.  

---

## 🧠 Model Architecture
- *Base Model*: [U-Net](https://arxiv.org/abs/1505.04597) (well-suited for pixel-level segmentation).  
- *Input*: 12-channel multispectral/optical images.  
- *Output*: Binary segmentation mask (water vs non-water).  

---

## 📊 Evaluation Metrics
We evaluate performance using segmentation metrics:
- *IoU (Intersection over Union)*  
- *Precision*  
- *Recall*  
- *F1-Score*  

---

## 🚀 Installation & Usage
### ⿡ Clone the repository
```bash
git clone https://github.com/Muhammed-AlReay/Water_Segmentation_using_Multispectral_and_optical_Data
cd Water_Segmentation_using_Multispectral_and_optical_Data
