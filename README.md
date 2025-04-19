# 🧠 Examining Alzheimer's Disease with Multimodal Deep Learning

**Author:** Alannah Cullinane Cooney  
**Degree:** BSc (Hons) in Software Development  
**Institution:** Munster Technological University – Cork  
**Supervisor(s):** Jing Hua Ye & Ruairi O'Reilly  
**Date:** May 2024

---

## 📘 Project Overview

This project presents a hybrid ensemble approach for classifying **Alzheimer’s Disease** using **deep learning** and **machine learning** techniques. The system fuses insights from three key modalities:
- MRI Imaging
- APOE Genetic Data
- CSF Biomarkers

A **pre-trained VGG16 CNN** is used to extract image features from MRI scans, which are then integrated with preprocessed APOE and CSF data to form a robust multimodal pipeline.

---

## ❓ Research Objectives

- Investigate whether a **hybrid deep learning model** improves accuracy in Alzheimer’s prediction.
- Evaluate the contribution of **VGG16-based image preprocessing** in enhancing performance.
- Compare traditional versus deep learning-based feature extraction methods in a medical context.

---

## ⚙️ System Architecture

- **Feature Extraction:**
  - MRI images processed using **VGG16** (transfer learning)
  - CSF and APOE data cleaned and refined using **K-NN for outlier handling**
  
- **Model:**
  - **Multilayer Perceptron (MLP)** ensemble classifier
  - Data split: 90% training (2,700 samples), 10% testing (300 samples)
  - Validation: **10-fold Cross-Validation**

- **Performance Metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - AUC-ROC

---

## 📊 Key Results

| Model Type              | Accuracy   | AUC-ROC |
|-------------------------|------------|---------|
| Traditional ML Baseline | 94.9%      | -       |
| **Hybrid (VGG16 + MLP)**| **96.67%** | 0.96    |

> 📈 VGG16 significantly improved feature extraction and model accuracy.

---

## ✅ Conclusion

- VGG16-enhanced feature extraction results in more accurate and generalizable classification.
- Multimodal learning (images + biomarkers + genetic data) provides a richer, more reliable diagnostic model.
- The ensemble framework outperformed single-modality and non-deep learning approaches.

---

## 📚 Reference

Yubraj, et al. (2019). *Prediction and Classification of Alzheimer’s disease based on Combined Features from Apolipoprotein-E Genotype, Cerebrospinal Fluid, MRI, and FDG-PET Imaging Biomarkers.*

---

## 💡 Future Work

- Improve explainability of AI predictions for medical review.
- Add support for additional biomarkers (e.g., blood-based).
- Experiment with other pre-trained architectures (e.g., ResNet, EfficientNet).



![FYP](https://github.com/user-attachments/assets/97650d7c-15d8-4681-bfb0-1f5fa3f1a2bc)
