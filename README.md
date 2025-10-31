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

<img width="647" height="398" alt="image" src="https://github.com/user-attachments/assets/59033fd4-c55c-451f-b268-6c5e46200b47" />


---

### 🧩 Image Distribution by Class and Split

<img width="717" height="437" alt="image" src="https://github.com/user-attachments/assets/2bd48cfa-fb0d-436a-9997-447467b43116" />


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

<img width="751" height="358" alt="image" src="https://github.com/user-attachments/assets/e365fcca-c07c-4e38-94bd-6bfce32d3dc2" />

---

### 🧾 Detailed Results

#### 📌 Ensemble Model (98.74% Accuracy)

| Metric | Glioma | Meningioma | No Tumor | Pituitary |
|---------|--------|-------------|-----------|------------|
| Precision | 1.00 | 0.97 | 0.98 | 1.00 |
| Recall | 0.96 | 0.99 | 1.00 | 1.00 |
| F1-Score | 0.98 | 0.98 | 0.99 | 1.00 |

<img width="540" height="388" alt="image" src="https://github.com/user-attachments/assets/40cb0e79-8bf3-4575-b478-55439b10adec" />

---

## 🔥 Grad-CAM Visualization

Below are Grad-CAM outputs for different models highlighting tumor-affected regions.

<img width="734" height="187" alt="image" src="https://github.com/user-attachments/assets/fb3e3388-69b2-46c7-bf54-74f0650855cf" />


---

## 📊 Training Visualization

You can also add:

- 📈 **Accuracy and Loss Curves**
  <img width="722" height="185" alt="image" src="https://github.com/user-attachments/assets/34820363-42ed-4d06-859c-7ae23996bef5" />

- 🧮 **Confusion Matrix**
  
  <img width="507" height="364" alt="image" src="https://github.com/user-attachments/assets/3ee8a570-5d9b-4330-b718-700d3b5c1663" />

  <img width="510" height="376" alt="image" src="https://github.com/user-attachments/assets/43912a02-3ab0-4545-aedf-d00127b1c551" />

  <img width="511" height="371" alt="image" src="https://github.com/user-attachments/assets/4873dca5-a10d-46e9-bc22-95086b46eae7" />

  <img width="515" height="386" alt="image" src="https://github.com/user-attachments/assets/ffdd7045-f365-4c1c-898b-099b7ad834c2" />

- 🔍 **Sample Predictions**

<img width="718" height="281" alt="image" src="https://github.com/user-attachments/assets/ec268bb4-39a4-4c8f-af81-ae41eeea2233" />
<img width="742" height="315" alt="image" src="https://github.com/user-attachments/assets/d64a7784-42e0-499e-8737-fb1e8569111a" />
<img width="739" height="313" alt="image" src="https://github.com/user-attachments/assets/fc87455f-be6e-4362-a33a-951fe9280753" />
<img width="738" height="289" alt="image" src="https://github.com/user-attachments/assets/66e03306-8a3a-40ea-ac5d-9f17dd44f5b8" />

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
- [Dataset Source (Kaggle)][(https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)(https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset))]

---

💡 *Created by [Abdullah Al Mahmud Joy](https://www.kaggle.com/abdullahalmahmudjoy)*  
B.Sc. in CSE | Teaching Assistant at BUBT | AI & Deep Learning Enthusiast  

---
⭐ **If you find this project useful, please give it a star on GitHub!**
