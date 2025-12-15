# Efficient Hyperspectral Image Classification using Spectral–Spatial Analysis

This project focuses on improving hyperspectral image analysis by exploring efficient dimensionality reduction and spectral–spatial feature fusion techniques. The goal is to classify land-cover materials from invisible wavelength information using benchmark hyperspectral data.

The project is directly aligned with modern diagnostic imaging research using hyperspectral technology — enabling richer material and tissue identification than standard RGB imaging.

---

## 🌈 What is Hyperspectral Imaging?

Hyperspectral cameras capture **100+ wavelengths** beyond visible light  
(UV–Visible–IR).  
Each pixel is represented as a **spectral signature** — a high-dimensional vector indicating its unique material composition.

Example shape:
Height × Width × Bands
145 × 145 × 220

---

##  Objective

The objective of this project is to build a **baseline classification pipeline using spectral signatures**, enhance its efficiency and accuracy through **dimensionality reduction with PCA**, further improve performance by **integrating spatial context for spectral–spatial fusion**, and finally **evaluate all enhancements using standard classification metrics** to demonstrate the overall improvement of the system.

## 🛰️ Dataset
**Indian Pines Hyperspectral Dataset**  
Size: `(145 × 145 × 220)` spectral cube  
Classes: **16 land-cover categories** (agriculture + vegetation)  
Labels provided as **ground truth class map**

Dataset source (Kaggle):  
🔗 https://www.kaggle.com/datasets/abhijeetgo/indian-pines-hyperspectral-dataset
---

## 🧠 Techniques Used

| Category | Methods |
|---------|---------|
| Preprocessing | Normalization, noise handling |
| Visualization | Spectral band plots, GT map |
| Dimensionality Reduction | PCA |
| Classification Baseline | SVM, KNN |
| Spectral Similarity | Spectral Angle Mapper (SAM) |
| Spatial Enhancement | Neighborhood filtering |

---

## 📊 Results (To Be Updated)
- Baseline classification vs improved model  
- Accuracy and computation time comparison  
- Spectral feature visualization  
- Confusion matrix for class performance 

## 📁 Repository Structure
```text
Hyperspectral-Classification
├── Data
│   ├── IPgt.npy
│   └── indianpinearray.npy
│
├── notebooks
│   ├── Hyperspectral_Image_Classification_Spectral_Spatial.ipynb
│
├── src
│   └── utils.py
│
├── results
│   ├── accuracy_comparison.png
│   ├── classification_map.png
│   └── spectral_signature_plots.png
│
├── report
│   └── Hyperspectral_Analysis_Report.pdf
│
└── README.md
```
## Techstack
- Python  
- NumPy, Pandas  
- scikit-learn  
- scikit-image / OpenCV  
- Matplotlib  
- Git + GitHub  
---
##  Future Work
- Apply CNN for spectral–spatial deep learning
- Extend to medical hyperspectral datasets when available
- Real-time hyperspectral segmentation
---

##  Author
**Saichandana** 

##  Acknowledgements
Indian Pines dataset originally captured by **AVIRIS sensor**  
Used widely in hyperspectral image classification research
> Better imaging → Earlier detection → Healthier future.
