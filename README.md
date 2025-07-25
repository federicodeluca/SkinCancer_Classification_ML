# 🧠 SkinCancer Classification on HAM10000

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

## 🧪 Techniques Implemented

| Section | Description |
|--------|-------------|
| CAP_2  | SVM binary & multiclass using metadata (age, sex, localization) |
| CAP_3  | Image loading and preprocessing (train/val/test split) |
| CAP_4  | SVM on raw pixels + handcrafted color features |
| CAP_5  | CNN (custom model) trained on full images |
| CAP_6  | Experimental CNN using image segmentation masks |

---

## ▶️ How to Run (in Colab)

You can open the notebook directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/federicodeluca/SkinCancer_Classification_ML/blob/main/ML_SkinCancer.ipynb)


