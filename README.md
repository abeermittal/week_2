# Week 2 – Dataset & Pre-processing

## 🎯 Objective
Collect a public waste-image dataset and plan preprocessing for the AI-Driven Waste Classification project (Sustainability theme).

## 🗂 Dataset Chosen
**Name:** Garbage Classification Dataset (Kaggle)  
**Classes:** Cardboard, Glass, Metal, Paper, Plastic, Trash (6 classes)  
**Reason for choice:** Clean, widely used, balanced categories, easy for transfer learning.

## 📁 Data Organization (Drive)
AI_Waste_Classification/
- dataset_raw/  ← unzipped Kaggle dataset
- dataset_clean/  ← will store resized/normalized/split data (planned)
- notebooks/  ← Colab notebook: `waste_preprocessing.ipynb`

## ⚙️ Planned Pre-processing (no code required this week)
- **Resize** all images to **224×224**  
- **Normalize** pixel values to **[0, 1]**  
- **Split** into **Train (80%)** and **Validation/Test (20%)**  
- **Organize folders** as:
  - dataset_clean/train/<class_name>/*
  - dataset_clean/val/<class_name>/*

## ✅ Week-2 Activities Completed
- Selected and downloaded Kaggle dataset for waste classification  
- Set up Google Drive folder structure for raw/clean data and notebooks  
- Outlined clear preprocessing steps and target image size  
- Prepared repository with Week-2 README and documentation

## 🧰 Tools (for next week’s execution)
Google Colab, Python, TensorFlow/Keras, NumPy, Matplotlib

## 📅 Week-3 Plan (Modeling)
- Use **transfer learning** (e.g., MobileNetV2)  
- Train on the cleaned dataset, evaluate accuracy  
- Save sample predictions for the final PPT
