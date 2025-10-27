# PyCaret Notebooks (GPU-Ready)

A compact, classroom-friendly collection of **PyCaret** notebooks covering:
- Binary & multiclass **classification**
- **Regression**
- **Clustering**
- **Anomaly detection**
- **Association rules** (PyCaret 2.3.5)
- **Time series** (univariate; with & without exogenous variables)
- Two **Gradio** demos (classification + forecasting)

> All notebooks run on **Colab** or locally. GPU is optional but recommended (set `use_gpu=True` in `setup()`).
>
> Datasets were chosen to avoid PyCaret’s official example notebooks.

---

## 📚 Notebooks

| File | Task | Open in Colab |
|---|---|---|
| `01_binary_classification_banknote.ipynb` | Binary classification (UCI Banknote) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samipn/Pycaret/blob/main/01_binary_classification_banknote.ipynb) |
| `02_multiclass_classification_wheat_seeds.ipynb` | Multiclass classification (Wheat Seeds) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samipn/Pycaret/blob/main/02_multiclass_classification_wheat_seeds.ipynb) |
| `03_regression_california_housing.ipynb` | Regression (California Housing) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samipn/Pycaret/blob/main/03_regression_california_housing.ipynb) |
| `04_clustering_wholesale_customers.ipynb` | Clustering (Wholesale Customers) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samipn/Pycaret/blob/main/04_clustering_wholesale_customers.ipynb) |
| `05_anomaly_detection_synthetic_outliers.ipynb` | Anomaly detection (synthetic with injected outliers) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samipn/Pycaret/blob/main/05_anomaly_detection_synthetic_outliers.ipynb) |
| `06_association_rules_groceries_pycaret235.ipynb` | Association rules (**pins `pycaret==2.3.5`**) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samipn/Pycaret/blob/main/06_association_rules_groceries_pycaret235.ipynb) |
| `07_timeseries_univariate_daily_min_temps.ipynb` | Time series: univariate forecasting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samipn/Pycaret/blob/main/07_timeseries_univariate_daily_min_temps.ipynb) |
| `08_timeseries_univariate_with_exog_pm25.ipynb` | Time series: univariate + exogenous variables | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samipn/Pycaret/blob/main/08_timeseries_univariate_with_exog_pm25.ipynb) |
| `09_gradio_banknote_demo.ipynb` | Gradio demo: banknote classifier | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samipn/Pycaret/blob/main/09_gradio_banknote_demo.ipynb) |
| `10_gradio_timeseries_demo.ipynb` | Gradio demo: univariate forecasting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samipn/Pycaret/blob/main/10_gradio_timeseries_demo.ipynb) |

> Notebook list pulled from this repo. :contentReference[oaicite:1]{index=1}

---

## 🚀 Run on Google Colab

1. Open any notebook via the **Colab** badge above.
2. *(Optional)* **Runtime → Change runtime type → GPU** (T4/L4 is fine).
3. Run the first `pip install` cell (version-pinned inside each notebook).
4. Run all cells.

**GPU note:** Only models that support GPU (e.g., XGBoost/CatBoost in classification/regression; some time-series models) will use it when `use_gpu=True` in `setup()`.

---
jupyter lab   # or jupyter notebook

