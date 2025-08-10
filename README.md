# Fear & Greed Index & Historical Data Analysis

## 📌 Overview

This project analyzes the **Fear & Greed Index** alongside **historical trading data** to explore patterns, correlations, and possible predictive relationships.
It uses **time-series analysis**, **PCA (Principal Component Analysis)**, **KMeans clustering**, and **Granger causality tests** to identify trends and dependencies between market sentiment and trading performance.

## 📂 Dataset

1. **fear\_greed\_index.csv**

   * Contains historical Fear & Greed Index values.
   * Columns may include: `date`, `value` (index score), and related metadata.

2. **historical\_data.csv**

   * Contains trading statistics for different days.
   * Includes columns like: `timestamp`, `pnl_num`, `volume_num`, etc.

## 🛠 Features

* **Data Parsing**

  * Robust date parsing with fallback for timestamps in milliseconds.
  * Flexible detection of date/value columns.
* **Data Visualization**

  * Line plots, scatter plots, and trend analysis using **Matplotlib** and **Seaborn**.
* **Statistical Analysis**

  * Daily aggregation of trading stats.
  * PCA for dimensionality reduction.
  * KMeans clustering to identify behavioral market states.
  * Granger causality tests to explore potential predictive relationships.

## 📦 Requirements

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

## ▶️ How to Run

1. Place `fear_greed_index.csv` and `historical_data.csv` in the same directory as the notebook.
2. Open the notebook:

```bash
jupyter notebook Notebook_1.ipynb
```

3. Run all cells sequentially to:

   * Load & parse the datasets.
   * Perform EDA & visualization.
   * Apply clustering & statistical analysis.
   * View and save plots.

## 📊 Outputs

* Cleaned and merged datasets with parsed dates.
* Saved visualizations (`.png`) for each analysis step.
* Summary statistics and model results.

## 📜 License

This project is licensed under the MIT License.

---

