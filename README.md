# 🧠 Explainable Brain Tumor Classification Using Transfer Learning and Grad-CAM on MRI Images
## 📌 Overview

This repository contains the complete source code, training scripts, and Grad-CAM visualization tools for our study on explainable brain tumor classification from MRI images.

## 📊 Dataset

We use the **Brain Tumor MRI Dataset** publicly available on Kaggle.

| Class | Description | Training (approx.) | Testing | Total |
|---|---|---|---|---|
| Glioma | Malignant brain tumor | 1400 | 400 | 1800 | 
| Meningioma | Typically benign tumor | 1400 | 400 |1800 |
| Pituitary | Pituitary gland tumor | 1400 | 400 |1800 |
| No Tumor | Healthy brain MRI | 1400 | 400 |1800 |

**Download:** [https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

After downloading, place the data as follows:
```
data/
├── Training/
│   ├── glioma/
│   ├── meningioma/
│   ├── notumor/
│   └── pituitary/
└── Testing/
    ├── glioma/
    ├── meningioma/
    ├── notumor/
    └── pituitary/
```
