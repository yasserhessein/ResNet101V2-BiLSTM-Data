# Pneumonia Classifiction ResNet101V2-BiLSTM Model

A hybrid deep learning model combining ResNet101V2 and Bidirectional LSTM for accurate pneumonia classification from chest X-ray images, developed by Dr. Yasir Hussein Shakir.




<img width="300" height="195" alt="image" src="https://github.com/user-attachments/assets/2922c054-35b5-481e-acd0-ddf85b6d5391" />


## 📋 Overview

This project implements a hybrid deep learning model for the automatic detection of pneumonia from pediatric chest X-ray images. The proposed architecture integrates **ResNet101V2** for spatial feature extraction and **Bidirectional LSTM (BiLSTM)** for capturing long-range dependencies and contextual relationships, achieving state-of-the-art performance on the public chest X-ray dataset.

## 🚀 Features

- Hybrid CNN-BiLSTM architecture for enhanced feature representation
- Pretrained ResNet101V2 backbone with transfer learning
- BiLSTM layer for sequential dependency modeling
- Achieves **98.29% accuracy**, **99.12% precision**, and **98.83% F1-score**
- Statistical significance testing (paired t-test with bootstrap, α = 0.05)
- Class-wise performance analysis for normal vs. pneumonia cases
- Comprehensive ablation study demonstrating component contributions

## 📊 Model Performance

| Metric | Value |
|--------|-------|
| Accuracy | 98.29% |
| Precision | 99.12% |
| Recall | 98.54% |
| F1-Score | 98.83% |

## 🗂️ Dataset

The dataset used in this work is the publicly available **Chest X-ray dataset** [32] from Guangzhou Women and Children's Medical Center, containing:
- **5,856 chest X-ray images**
- **4,273 pneumonia cases**
- **1,583 normal cases**
- Pediatric patients aged 1–5 years
- Anterior-posterior view images



## 📈 Results

The proposed ResNet101V2+BiLSTM model outperforms state-of-the-art methods:

| Method | Accuracy | Precision | Recall | F1-Score |
|--------|----------|-----------|--------|----------|
| Wang et al. [28] DenseNet+SE | 92.80% | 92.60% | 96.20% | 94.30% |
| Asswin et al. [26] Ensemble | 96.15% | 97.91% | 97.91% | 96.89% |
| Chen et al. [30] EfficientNetB0+DenseNet121 | 95.19% | 98.38% | 93.48% | 96.06% |
| **Ours (ResNet101V2+BiLSTM)** | **98.29%** | **99.12%** | **98.54%** | **98.83%** |

## 🔬 Statistical Validation

Statistical significance analysis confirmed that the addition of BiLSTM to ResNet101V2 resulted in **statistically significant improvements** (p < 0.05) across all evaluation metrics.


## 🛠️ Requirements

- Python 3.8+
- TensorFlow 2.14 / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Pandas



# 👨‍💻 Author

<div align="center">

**🧑‍🔬 Dr. Yasir Hussein Shakir**  
*AI Research Scientist | Artificial intelligence*



> ⚠️ **Note:** If you encounter any issues with this code, please don't hesitate to contact me.

## 📬 Contact Information

<div align="center">

| Platform | Address | Badge |
|----------|---------|-------|
| **🏫 Uniten** | `pe20911@uniten.edu.my` | ![Academic](https://img.shields.io/badge/%F0%9F%93%A7_Academic-00A2FF?style=flat-square) |
| **📮 Yahoo** | `yasserhesseinshakir@yahoo.com` | ![Personal](https://img.shields.io/badge/%F0%9F%93%A8_Personal-720E9E?style=flat-square) |
| **📚 Google Scholar** | [`Yasir Hussein`](https://scholar.google.com/citations?user=37iNJq0AAAAJ&hl=en) | ![Scholar](https://img.shields.io/badge/%F0%9F%93%9A_Scholar-4285F4?style=flat-square) |
| **🏆 Kaggle** | [`yasserhessein`](https://www.kaggle.com/yasserhessein) | ![Competitions](https://img.shields.io/badge/%F0%9F%A5%87_Competitions-20BEFF?style=flat-square) |
| **💻 GitHub** | [`yasserhessein`](https://github.com/yasserhessein) | ![Code](https://img.shields.io/badge/%F0%9F%90%99_Code-181717?style=flat-square) |
| **💼 LinkedIn** | [`Yasir Hussein`](https://www.linkedin.com/in/yasir-hussein-314a65201/) | ![Professional](https://img.shields.io/badge/%F0%9F%91%94_Professional-0077B5?style=flat-square) |

</div>
