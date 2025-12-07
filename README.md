# 🧠 Brain Tumor Detection using CNN  
Achieves **92% Recall & F1-score** and **81% test accuracy** on the Brain MRI Dataset

This project builds a Convolutional Neural Network (CNN) using **PyTorch** to classify brain MRI images as **tumor** or **no tumor**.  
The model achieves **high recall**, which is crucial for medical applications where missing a tumor is far more dangerous than a false positive.

---

## Features

- Custom PyTorch **Dataset** implementation  
- Clean and modular **CNN architecture**  
- Training & validation loops with:
  - Loss
  - Accuracy
  - Recall
  - F1-score
- Test set evaluation  
- Full-dataset final evaluation  
- Data exploration (EDA)  
- Model achieves **~0.94 Recall & F1** on test set  
- Lightweight: ~58k trainable parameters  
- Easy to run on **Google Colab**

---

## 📂 Project Structure
1. brain-tumor-detection.ipynb # Main notebook
2. README.md # Documentation
3. requirements.txt # Dependencies for running the project

---

## 📥 Dataset

This project uses the **Brain MRI Images for Brain Tumor Detection** dataset from Kaggle:

[https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/data)

The dataset consists of two folders:

- `yes/` → MRI images containing a tumor  
- `no/` → MRI images without a tumor  

Images are grayscale but converted to **RGB** for PyTorch.

---

## 🛠 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/brain-tumor-detection.git
cd brain-tumor-detection


