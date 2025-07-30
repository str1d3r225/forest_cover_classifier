# 🌲 Forest Cover Type Classification

This project applies supervised machine learning techniques to classify forest cover types using cartographic variables from the UCI Covertype dataset. It focuses on model performance comparison, feature importance, and interpretability using Random Forest and XGBoost.

---

## 📂 Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/covertype)
- **Shape:** 581,012 rows × 55 columns
- **Target:** Cover_Type (1 to 7), representing forest cover classes

---

## 📌 Objectives
- Classify forest cover types using environmental and soil features
- Compare performance between Random Forest and XGBoost
- Visualize confusion matrices and feature importances
- Save results in a professional and reusable format

---

## 🛠️ Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn (Random Forest)
- XGBoost
- Seaborn, Matplotlib

---

## 🔍 Key Features
- Clean preprocessing with no missing values
- Stratified train-test split
- Hyperparameter-ready model structure
- Saved charts in `/charts/` folder
- Scalable design for future tuning or deployment

---
## 📊 Models
| Model          | Accuracy |
|----------------|----------|
| Random Forest  | ~ 0.9533316695782381 % |
| XGBoost        | ~ 0.8696074972246843 % |

## 📈 Visualizations
- Confusion matrices
- Feature importance bar plots

## 🚀 How to Run
1. Clone this repo
2. Download dataset from [UCI](https://archive.ics.uci.edu/ml/datasets/covertype)
3. Place `Data/data.data` in `dataset/`
4. Run `forest_cover_classifier.ipynb`

---

