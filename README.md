# 🧠 Brain Tumor Detection with Hybrid Deep Learning

This is a beginner-level deep learning project focused on brain tumor detection using both medical imaging and gene expression data. The goal is to learn and experiment with hybrid models, not to achieve high accuracy—especially given the limited dataset and my early stage in machine learning.

## 🚀 Project Overview

- **Image Input**: Grayscale MRI scans resized to 256×256 pixels.
- **Label Format**: YOLO-style bounding box `.txt` files.
- **Gene Data**: Tabular gene expression values processed via PCA.
- **Models Built**:
  - CNN for bounding box regression.
  - CNN for image classification.
  - Hybrid model combining image and gene features.

## 🧪 Key Steps

1. **Preprocessing**:
   - Normalize grayscale images.
   - Resize to 256×256.
   - Parse YOLO-style bounding box labels.

2. **Modeling**:
   - Build a CNN for bounding box prediction.
   - Train a CNN classifier for tumor type.
   - Apply PCA to gene data and merge with image features.

3. **Evaluation**:
   - Mean Squared Error (MSE) for box regression.
   - Classification report for CNN and hybrid models.

## ⚠️ Limitations

- **Small Dataset**: Only ~250 images and limited gene samples.
- **Beginner Code**: This project is part of my learning journey.
- **Low Accuracy**: Models are underfitting due to data scarcity and basic architecture.

## 🛠️ Technologies Used

- Python, OpenCV, NumPy, Pandas
- TensorFlow / Keras
- Scikit-learn (PCA, metrics)
- Matplotlib

## 🎯 Learning Goals

- Understand image preprocessing and CNN architecture.
- Learn how to handle bounding box regression.
- Experiment with combining image and tabular data.
- Practice model evaluation and interpretation.

## 📌 Next Steps

- Increase dataset size (images + gene samples).
- Improve label quality and format consistency.
- Try data augmentation and regularization.
- Explore transfer learning with pretrained models.

## 📫 Contact
Feel free to reach out via LinkedIn or GitHub for collaboration or freelance opportunities.
\https://www.linkedin.com/in/alireza-sobhani-385134245
