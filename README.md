# 🌌 Habitability of Exoplanets
**Machine Learning–Based Analysis of Exoplanet Detection and Habitability**

This project presents a **data-driven study on exoplanet detection and habitability assessment** using **machine learning and deep neural networks**, leveraging the **NASA Exoplanet Archive Dataset**. The work explores how supervised learning models can assist astronomers in identifying exoplanets and estimating their potential habitability from observational data.

---

## 🔍 Background & Motivation
Exoplanets are commonly detected through variations in starlight, such as transit-based light curves. Although missions like **Kepler** have significantly expanded exoplanet catalogs, **manual and heuristic-based analysis of light curves is time-intensive and difficult to scale**.

This motivates the use of **machine learning techniques** capable of learning complex, non-linear patterns from large astrophysical datasets, enabling faster and more systematic exoplanet characterization.

---

## 🧠 Methodology
The study integrates classical machine learning and neural approaches to address two tasks:

### 1️⃣ Exoplanet Detection
- Applied **Artificial Neural Networks (ANNs)** to classify exoplanet candidates  
- Learned complex patterns in observational features derived from astrophysical data  
- Achieved **88.3% accuracy** on held-out test data  

### 2️⃣ Habitability Prediction
- Modeled planetary and stellar attributes relevant to habitability  
- Used **Gradient Boosting** for predictive modeling  
- Achieved **91.06% accuracy** in habitability classification  

---

## 📊 Dataset
- **NASA Exoplanet Archive Dataset**
- Includes planetary, orbital, and stellar features used for detection and habitability analysis

---

## 🛠️ Tech Stack
- Python  
- NumPy / Pandas  
- Scikit-learn  
- Artificial Neural Networks (ANNs)  
- Gradient Boosting Models  
- Jupyter Notebook  

---

## 📈 Results
| Task | Model | Accuracy |
|---|---|---|
| Exoplanet Detection | ANN | **88.3%** |
| Habitability Prediction | Gradient Boosting | **91.06%** |

---

## 📝 Notes
- This project is intended for **research and exploratory analysis**
- Results depend on dataset quality and feature availability
- Focuses on **methodological insights**, not mission-level deployment
