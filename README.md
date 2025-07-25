# 🧠 SkinCancer Classification on HAM10000

![Jupyter Notebook](https://img.shields.io/badge/format-Jupyter%20Notebook-orange)
![ML Project](https://img.shields.io/badge/Machine%20Learning-SVM%20%7C%20CNN-blue)
![Dataset: HAM10000](https://img.shields.io/badge/dataset-HAM10000-lightgrey)
![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/federicodeluca/SkinCancer_Classification_ML/blob/main/ML_SkinCancer.ipynb)

This project applies both classical Machine Learning and Deep Learning techniques to classify skin lesion images using the **HAM10000** dataset.

The dataset includes dermatoscopic images labeled into **7 categories**, and the project explores various modeling strategies:  
- SVM with metadata  
- SVM using image pixel features  
- Custom CNN
- CNN with segmentation masks

---

## 📂 Dataset: HAM10000
- Source: [Kaggle](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
- 10,015 dermoscopic images
- 7 classes: `akiec`, `bcc`, `bkl`, `df`, `nv`, `mel`, `vasc`

---

##  🧱 Project Structure
| Section | Description |
|--------|-------------|
| CAP_1  | Project overview, motivation and dataset introduction |
| CAP_2  | SVM binary & multiclass using metadata (age, sex, localization) |
| CAP_3  | Image loading and preprocessing (train/val/test split) |
| CAP_4  | SVM on raw pixels + handcrafted color features |
| CAP_5  | Custom CNN model trained on dermoscopic images |
| CAP_6  | Experimental CNN using image segmentation masks |
| CONCLUSIONI | Summary of findings, comparison of models and future work |
---

## ▶️ How to Run (in Colab)

You can open the notebook directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/federicodeluca/SkinCancer_Classification_ML/blob/main/ML_SkinCancer.ipynb)


