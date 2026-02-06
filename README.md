# Feature-Aware CNN Architectures for Network Intrusion Detection

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Kaggle Dataset](https://img.shields.io/badge/Kaggle-TII--SSRC--23-red.svg)](https://www.kaggle.com/datasets/daniaherzalla/tii-ssrc-23)

This repository contains Jupyter notebooks implementing **feature-aware CNN models** for network intrusion detection using the **TII-SSRC-23 dataset**. The project evaluates three CNN architectures—baseline CNN, Feature Weight Map CNN (FWM-CNN), and Sliding Window Correlation Coefficient CNN (SWCC-CNN)—across different classification tasks.

The TII-SSRC-23 dataset is available on Kaggle: [TII-SSRC-23 Dataset](https://www.kaggle.com/datasets/daniaherzalla/tii-ssrc-23)

---

## Notebooks

1. **Data_Preprocessing.ipynb**  
   Preprocessing of the TII-SSRC-23 dataset, including data cleaning, feature extraction, normalization, and handling class imbalance.

2. **binary_classification.ipynb**  
   Binary classification of network traffic (benign vs malicious) using CNN, FWM-CNN, and SWCC-CNN architectures.

3. **Traffic_type_classification.ipynb**  
   Multiclass classification based on the main traffic types (e.g., Audio, Video, DoS) using the three CNN models.

4. **Traffic_subtype_classification.ipynb**  
   Multiclass classification based on traffic subtypes for more detailed intrusion detection using feature-aware CNN models.

---

## Features

- Baseline CNN, FWM-CNN, and SWCC-CNN implementations for network traffic classification.
- Supports binary, multiclass, and subtype-level classification.
- Incorporates feature weighting and correlation-based enhancements.
- Fully reproducible with Jupyter notebooks.

---
## Project Team

**Students:**  
- Abdelaziz Ariri  
- Ossama Ettaqafi  

**Supervisor:**  
- Prof. Ali Kartit


