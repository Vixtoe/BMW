# BMW Sales Classification & Analysis

> Machine learning modeling and exploratory data analysis on 50,000 global BMW sales records (2010–2024) to predict sales performance and evaluate regional purchasing behaviors.

---

## Project Overview

This project analyzes a dataset of 50,000 BMW sales records spanning 2010 to 2024. The objective is twofold: build machine learning classification models to categorize sales performance (`High` vs. `Low`) based on vehicle specifications, and perform exploratory data analysis to evaluate hypotheses regarding regional car color preferences and engine sizing.

---

## Key Questions & Hypotheses

* **Sales Classification Performance:** Can vehicle specifications (Engine Size, Transmission, Fuel Type, Price) accurately predict binary sales volume tiers (`High` vs. `Low`)?
* **Regional Preference Hypothesis:** Does vehicle exterior color significantly impact sales volumes across different global markets and regions?
* **Model Evaluation:** What are the benchmark classification metrics (Accuracy, Precision, Recall, F1-Score) across predictive algorithms?

---

## Dataset Overview

The dataset contains 50,000 global transaction entries across 11 features:

* **Vehicle Attributes:** `Model` (e.g., 3 Series, 5 Series, 7 Series, X3, M5, i8), `Color`, `Fuel_Type` (Petrol, Diesel, Hybrid, Electric), `Transmission` (Manual, Automatic), `Engine_Size_L` (Cylinder displacement in Liters).
* **Usage & Commercials:** `Year` (2010–2024), `Mileage_KM`, `Price_USD`, `Sales_Volume`.
* **Geographic & Tiers:** `Region` (Asia, Europe, North America, South America, Middle East), `Sales_Classification` (`High`, `Low`).

---

## Machine Learning & Analytical Workflow

1. **Exploratory Data Analysis (EDA):** Feature distribution analysis across engine sizes, transmission types, and global region-color cross-tabulations.
2. **Data Preprocessing & Normalization:** Categorical encoding for region, fuel type, and transmission; numerical feature scaling on mileage, price, and engine displacement.
3. **Model Development:** Supervised classification modeling evaluating feature importance and classification metrics.
4. **Hypothesis Testing:** Statistical evaluation of regional preferences and feature correlations with overall sales tiers.

---
## Dataset & Resources

* **Dataset File:** [`data/BMW sales data (2010-2024).csv`](BMW_sales_data_(2010-2024).csv) (50,000 global transaction records).
* **Presentation Deck:** [View Presentation Slides (PDF)](docs/presentation.pdf)

---

## Tech Stack & Tools

* **Language:** Python
* **Data Processing & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Classification, Preprocessing, Evaluation Metrics)
* **Visualization:** Matplotlib, Seaborn
* **Data Source:** BMW Global Sales Dataset (2010–2024)

---

## Team & Individual Contributions

* **Team Members:** Chanoudom Tann (Me), Apivit Denpruktham
* **My Individual Role & Contributions:**
  * Cleaned and preprocessed the 50K-record dataset, handling categorical feature encodings and scaling.
  * Implemented machine learning classification algorithms to predict sales classification tiers.
  * Conducted feature importance analysis and produced visualization plots for presentation deliverables.

---

## Project Structure

```text
bmw-sales-classification/
├── docs/
│   ├── presentation.pdf
│   └── eda-charts/
├── notebooks/
│   └── sales_classification_analysis.ipynb
├── data/
│   └── bmw_sales_2010_2024.csv
└── README.md
