#  Natural Scene Image Classification

A deep learning model that classifies natural scene images into **6 categories** with **86% accuracy**, trained on the Intel Image Classification dataset.

---

##  Categories

| Label | Description |
|-------|-------------|
|  Buildings | Urban structures and architecture |
|  Forest | Dense trees and woodland areas |
|  Glacier | Ice formations and frozen landscapes |
|  Mountain | Mountain ranges and rocky terrain |
|  Sea | Ocean and seashore scenes |
|  Street | Roads and city streets |

---

##  Results

| Metric | Score |
|--------|-------|
| Overall Accuracy | **86%** |
| Macro F1-Score | **0.86** |
| Best Class (Forest) | **F1: 0.96** |

### Per-Class Performance

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Buildings | 0.79 | 0.91 | 0.85 |
| Forest | 0.95 | 0.97 | **0.96** |
| Glacier | 0.84 | 0.78 | 0.81 |
| Mountain | 0.82 | 0.80 | 0.81 |
| Sea | 0.87 | 0.88 | 0.87 |
| Street | 0.89 | 0.84 | 0.87 |

---

##  Dataset

- **Source:** [Intel Image Classification – Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)
- **Test Set Size:** 3,000 images
- **Downloaded via:** Kaggle API

---

##  Tech Stack

- **Language:** Python 3.12
- **Framework:** TensorFlow / Keras
- **Environment:** Google Colab (GPU: T4)
- **Dataset Access:** Kaggle API
