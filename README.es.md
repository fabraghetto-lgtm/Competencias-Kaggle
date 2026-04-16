# Competencias-Kaggle

> 🇬🇧 [English version available in README.md](README.md)

Repositorio personal con notebooks de competencias de Kaggle, que incluye análisis exploratorio de datos (EDA) y pipelines de machine learning.

---

## 📁 Estructura del Repositorio

```
Competencias-Kaggle/
├── irrigation need/       # Competencia de predicción de necesidad de riego
│   ├── eda.ipynb          # Análisis Exploratorio de Datos
│   └── preprocessing.ipynb # Preprocesamiento y pipeline de ML
└── starters/              # Notebooks introductorios para competencias básicas
    ├── eda.ipynb
    └── kaggle/
        └── eda.ipynb      # EDA para una competencia básica de Kaggle
```

---

## 🌱 Irrigation Need

Competencia de clasificación multiclase para predecir la necesidad de riego de cultivos.

**Notebooks:**

- **`eda.ipynb`** — Análisis exploratorio que incluye estadísticas descriptivas, matriz de correlación y detección de outliers.
- **`preprocessing.ipynb`** — Pipeline completa de ML:
  - Carga de datos y separación en conjuntos de entrenamiento/prueba
  - Transformación de columnas (imputación, escalado, codificación one-hot)
  - Entrenamiento de modelo multiclase con `OneVsRestClassifier` + `LinearSVC`
  - Evaluación del modelo

**Variables principales:** `Rainfall_mm` y otras características agronómicas utilizadas para predecir la categoría de necesidad de riego.

---

## 📚 Starters

Notebooks introductorios para comenzar con competencias de Kaggle.

- **`starters/kaggle/eda.ipynb`** — EDA para una competencia básica de predicción de ventas en series temporales, explorando datasets como `train.csv`, `oil.csv`, `stores.csv` y `transactions.csv`.

---

## 🛠 Tecnologías

- Python 3
- pandas, scikit-learn, seaborn, matplotlib
- Jupyter Notebooks

---

## 📝 Notas

- Todos los notebooks están escritos principalmente en español.
- Los archivos de datos (`.csv`) no están incluidos en el repositorio — descargalos directamente desde las páginas de las competencias correspondientes en Kaggle.
