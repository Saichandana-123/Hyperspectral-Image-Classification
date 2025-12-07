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

## 🎯 Objective

✔ Build a **baseline** classification pipeline using spectral signatures  
✔ Improve efficiency and accuracy using dimensionality reduction (PCA)  
✔ Integrate **spatial context** for spectral–spatial fusion  
✔ Evaluate enhancements using standard classification metrics  

---

## 🛰️ Dataset

**Indian Pines Hyperspectral Dataset**  
Size: `(145 × 145 × 220)` spectral cube  
Classes: **16 land-cover categories** (agriculture + vegetation)  
Labels provided as **ground truth class map**

Dataset Source: Publicly available hyperspectral benchmark

Ground Truth Meaning:
- Each pixel labeled with class ID (1–16)
- `0` generally indicates background/unlabeled region

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

✔ Baseline classification vs improved model  
✔ Accuracy and computation time comparison  
✔ Spectral feature visualization  
✔ Confusion matrix for class performance  

(Plots and result tables will be added here as work progresses)

---

## 📁 Repository Structure
Hyperspectral-Classification/
│
├── Data/ # Dataset files (.npy)
│ ├── Indian_pines.npy
│ ├── Indian_pines_GT.npy
│
├── notebooks/ # Jupyter notebooks
│ ├── 01_preprocessing.ipynb
│ ├── 02_baseline_model.ipynb
│ ├── 03_pca_and_spatial.ipynb
│
├── src/ # Helper code modules
│ ├── utils.py
│
├── results/ # Saved outputs (plots, accuracy tables)
│
└── README.md # Project documentation

---

## 🧰 Tech Stack

- Python  
- NumPy, Pandas  
- scikit-learn  
- scikit-image / OpenCV  
- Matplotlib  
- Git + GitHub  

---

## 🌟 Future Work

- Apply CNN for spectral–spatial deep learning
- Extend to medical hyperspectral datasets when available
- Real-time hyperspectral segmentation

---

## ✨ Author

**Your Name**  
Aspiring researcher in AI-based imaging systems  
Focused on hyperspectral analysis for healthcare & scientific exploration

---

## 📌 Acknowledgements

Indian Pines dataset originally captured by **AVIRIS sensor**  
Used widely in hyperspectral image classification research

---

> Better imaging → Earlier detection → Healthier future.

