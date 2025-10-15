# 🧠 Ensemble Deep Learning for Brain Tumor Classification

This project focuses on **ensemble deep learning techniques** for classifying brain tumors (Glioma, Meningioma, Pituitary, and No-Tumor) from MRI scans.  
The work combines multiple CNN architectures to boost prediction accuracy and interpretability.

---

## 📘 Kaggle Notebook

[![Open in Kaggle](https://img.shields.io/badge/Kaggle-Open%20Notebook-blue?logo=kaggle)](https://www.kaggle.com/code/abdullahalmahmudjoy/ensemble-deep-learning-for-brain-tumor-classifica?scriptVersionId=266878172)

---

## 📊 Dataset Overview

✅ **Class-wise Count After Balancing (2500 per class):**

| Class       | Count |
|--------------|--------|
| Glioma       | 2500   |
| Meningioma   | 2500   |
| Pituitary    | 2500   |
| No Tumor     | 2500   |

---

### 🧩 Image Distribution by Class and Split

![Image Distribution](path/to/your_first_image.png)  
*(Replace the path with your actual image name, e.g. `24b60cbf-0e3c-4844-8697-08c09a9cde36.png`)*

---

## 🧠 Model Architectures Used

- **Custom CNN**
- **VGG16**
- **MobileNetV2**
- **EfficientNetB0**
- **Ensemble Model** (combining all above)

---

## 📈 Model Performance Summary

| Model          | Accuracy | Precision | Recall | F1-Score |
|----------------|-----------|------------|---------|-----------|
| CustomCNN      | 0.9684    | 0.9684     | 0.9681  | 0.9680    |
| VGG16          | 0.9718    | 0.9724     | 0.9717  | 0.9718    |
| MobileNetV2    | 0.9752    | 0.9754     | 0.9751  | 0.9751    |
| EfficientNetB0 | 0.9718    | 0.9719     | 0.9719  | 0.9718    |
| 🧩 **Ensemble** | **0.9874** | **0.9875** | **0.9873** | **0.9872** |

---

### 🧾 Detailed Results

#### 📌 Ensemble Model (98.74% Accuracy)

| Metric | Glioma | Meningioma | No Tumor | Pituitary |
|---------|--------|-------------|-----------|------------|
| Precision | 1.00 | 0.97 | 0.98 | 1.00 |
| Recall | 0.96 | 0.99 | 1.00 | 1.00 |
| F1-Score | 0.98 | 0.98 | 0.99 | 1.00 |

---

## 🔥 Grad-CAM Visualization

Below are Grad-CAM outputs for different models highlighting tumor-affected regions.

![Grad-CAM Comparison](path/to/your_second_image.png)  
*(Replace the path with your actual Grad-CAM image name, e.g. `ab192189-034e-42b4-83d8-fdec23542c61.png`)*

---

## 📊 Training Visualization

You can also add:

- 📈 **Accuracy and Loss Curves**
- 🧮 **Confusion Matrix**
- 🔍 **Sample Predictions**

*(Just upload those plots and reference them like the others above.)*

---

## ⚙️ Workflow

1. **Data Preprocessing** → normalization, resizing, and augmentation  
2. **Model Training** → fine-tuning pretrained CNNs  
3. **Ensemble Creation** → weighted averaging of predictions  
4. **Visualization** → Grad-CAM for interpretability  
5. **Evaluation** → accuracy, precision, recall, F1-score  

---

## 🧾 References

- [Kaggle Notebook](https://www.kaggle.com/code/abdullahalmahmudjoy/ensemble-deep-learning-for-brain-tumor-classifica?scriptVersionId=266878172)
- [Dataset Source (Kaggle)](https://www.kaggle.com/datasets)

---

💡 *Created by [Abdullah Al Mahmud Joy](https://www.kaggle.com/abdullahalmahmudjoy)*  
B.Sc. in CSE | AI & Deep Learning Enthusiast  

