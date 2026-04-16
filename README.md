# Competencias-Kaggle

> 🇪🇸 [Versión en español disponible en README.es.md](README.es.md)

A personal repository of Kaggle competition notebooks, including exploratory data analysis (EDA) and machine learning pipelines.

---

## 📁 Repository Structure

```
Competencias-Kaggle/
├── irrigation need/       # Irrigation Need prediction competition
│   ├── eda.ipynb          # Exploratory Data Analysis
│   └── preprocessing.ipynb # Data preprocessing & ML pipeline
└── starters/              # Starter notebooks for basic Kaggle competitions
    ├── eda.ipynb
    └── kaggle/
        └── eda.ipynb      # EDA for a basic Kaggle competition
```

---

## 🌱 Irrigation Need

Multiclass classification competition to predict the irrigation needs of crops.

**Notebooks:**

- **`eda.ipynb`** — Exploratory analysis including descriptive statistics, correlation matrix, and outlier detection.
- **`preprocessing.ipynb`** — Full ML pipeline:
  - Data loading and train/test split
  - Column transformation (imputation, scaling, one-hot encoding)
  - Multiclass model training with `OneVsRestClassifier` + `LinearSVC`
  - Model evaluation

**Key variables include:** `Rainfall_mm` and other agronomic features used to predict irrigation need category.

---

## 📚 Starters

Introductory notebooks for getting started with Kaggle competitions.

- **`starters/kaggle/eda.ipynb`** — EDA for a basic time-series sales forecasting competition, exploring datasets such as `train.csv`, `oil.csv`, `stores.csv`, and `transactions.csv`.

---

## 🛠 Tech Stack

- Python 3
- pandas, scikit-learn, seaborn, matplotlib
- Jupyter Notebooks

---

## 📝 Notes

- All notebooks are written primarily in Spanish.
- Data files (`.csv`) are not included in the repository — download them directly from the respective Kaggle competition pages.
