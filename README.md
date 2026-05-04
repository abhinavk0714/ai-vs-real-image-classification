# Detecting AI-Generated vs Real Images

## Overview
This project compares classical machine learning models and convolutional neural networks (CNNs) for classifying images as real or AI-generated.

The focus is on understanding how data representation impacts performance in image classification tasks.

---

## Methods
- Logistic Regression (+ PCA)
- SVM (+ PCA)
- CNN (baseline)
- CNN (improved)

Images were resized to 64×64 and normalized. Classical models use flattened inputs, while CNNs operate on image tensors.

---

## Results

| Model | Accuracy |
|------|--------|
| Logistic Regression | ~75% |
| SVM | ~79% |
| CNN (Baseline) | ~86% |
| CNN (Improved) | ~88% |

**Key takeaway:** CNNs outperform classical models by preserving spatial structure.

---

## Dataset
Kaggle dataset:  
https://www.kaggle.com/datasets/rhythmghai/ai-vs-real-images-dataset

---

## Files
- `ai_generated_vs_real_image_classification.ipynb` – implementation
- `ai_generated_vs_real_images_machine_learning_report.pdf` – report

---

## Tech Stack
Python, scikit-learn, PyTorch, NumPy, Matplotlib
