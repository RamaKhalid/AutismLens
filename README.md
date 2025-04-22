# 🧠 AutismLens

**AutismLens** is a deep learning-based project focused on improving the early diagnosis of Autism Spectrum Disorder (ASD) using facial image analysis. This project integrates advanced CNN architectures, particularly **ConvNeXt**, with interpretability tools like **Grad-CAM** to provide accurate and explainable predictions. The system is designed to assist clinicians and researchers in identifying ASD-related patterns through facial features.

---

## 🎯 Goals

- Early, explainable detection of ASD through facial image recognition.
- Improve diagnostic accuracy and speed using advanced AI.
- Provide a simple and interpretable tool for researchers and clinicians.

---
## 🧩 How It Works

1. Upload a facial image of a child.
2. The model predicts whether the child is likely to be on the autism spectrum or not.
3. Grad-CAM highlights key facial features used in the prediction for better interpretability.
4. Results are displayed on the web interface.

---


## 📂 Datasets Used

1. **Autism vs. Healthy Children**  
   📥 [Kaggle Dataset – Autism Image Data](https://www.kaggle.com/datasets/cihan063/autism-image-data)

2. **Neurodevelopmental Disorders (NDD)**  
   📥 [Roboflow Dataset – Down Syndrome Facial Images](https://universe.roboflow.com/shreeya-ywxmu/ds-pranf/dataset/1)

3. **Other Sources (NDD Syndromes)**  
   Additional facial images for the following syndromes were obtained from various open-access sources:
   - 22q11.2 Deletion Syndrome  
   - 22q11.2 Duplication Syndrome  
   - Fragile X Syndrome  
   - Williams-Beuren Syndrome  
   - Cerebral Palsy Disorder
---

## 📊 Model Performance

| Model                 | Accuracy (%) | Precision (%) | Recall (%) | F1-Score (%) |
|----------------------|--------------|----------------|-------------|----------------|
| **ConvNeXt**              | 92%          | 92%            | 92%         | 92%            |
| Vision Transformer (ViT) | 88%          | 88%            | 88%         | 88%            |
| DenseNet121              | 87%          | 87%            | 87%         | 87%            |
| EfficientNet_b0          | 87%          | 87%            | 87%         | 87%            |
| ResNet50                 | 89%          | 89%            | 89%         | 89%            |

---

## 💡 Key Technologies (Tools)



---


