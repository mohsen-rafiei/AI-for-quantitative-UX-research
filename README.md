[README.md](https://github.com/user-attachments/files/26324607/README.md)
# AI and Advanced Analytics in UX Research

Hands-on workshop materials for teaching practical analytics methods in UX research using a single Jupyter notebook and reusable synthetic datasets.

## Project Overview

This project demonstrates four high-impact analytics workflows for UX decision-making:

1. **Tabular foundation models (TabPFN v2)** for supervised UX risk prediction.
2. **Clustering (K-means and DBSCAN)** for behavioral segmentation.
3. **Anomaly detection** for identifying unusual sessions.
4. **Time series analysis** for trend, seasonality, intervention analysis, and forecasting.

The notebook is designed for live instruction with:
- business/UX context framing,
- step-by-step analysis cells,
- visual outputs,
- plain-language interpretation notes.

## Repository Contents

- `ux_ai_advanced_analytics_workshop.ipynb` - Main workshop notebook.
- `ux_tabpfn_dataset.csv` - Dataset for supervised classification.
- `ux_clustering_dataset.csv` - Dataset for user behavior clustering.
- `ux_anomaly_dataset.csv` - Dataset for anomaly detection.
- `ux_time_series_dataset.csv` - Dataset for time-series modeling and forecasting.

## Requirements

- Python 3.10+
- Jupyter Notebook or JupyterLab

Core libraries used:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`
- `tabpfn` (optional fallback logic is included in the notebook if unavailable)


## Notebook Structure

### Section 1: TabPFN v2 for UX Risk Prediction
- Predicts users likely to report poor onboarding experience.
- Compares baseline logistic regression vs TabPFN.
- Highlights practical model evaluation (Accuracy, F1, ROC AUC) and risk-based prioritization.

### Section 2: Behavioral Segmentation
- Uses K-means for compact segment discovery.
- Uses DBSCAN for irregular clusters and noise/outlier detection.
- Includes cluster profiling and PCA visualization for teaching-friendly interpretation.

### Section 3: UX Anomaly Detection
- Applies Isolation Forest and Local Outlier Factor.
- Evaluates with hidden labels for demonstration.
- Shows analyst triage flow with top abnormal session ranking.

### Section 4: Time Series UX Analytics
- Explores trend and seasonality decomposition.
- Builds Holt-Winters forecast with time-aware split.
- Compares pre/post redesign metric windows for intervention insight.



## Notes

- Datasets are synthetic but designed to resemble realistic UX telemetry patterns.
- Keep all CSV files in the same directory as the notebook for direct loading.

## Author

Mohsen Rafiei, Ph.D., Bahareh Jozranjbar Ph.D.
