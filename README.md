# Finlatics-Data-Science

This project focuses on performing **Exploratory Data Analysis (EDA)** and predictive modeling for a Portuguese banking institution's marketing campaigns. The primary goal is to identify customer behaviors that lead to a term deposit subscription.

---

## 1. Banking Term Deposit Analysis
The module evaluates direct marketing efforts (phone calls) to identify potential customers likely to invest.

### Dataset Overview
* **Observations**: 45,211 records (May 2008 – November 2010).
* **Features**: 17 attributes including demographic data (age, job, education), financial status (balance, loans), and campaign metrics (duration, contact type).
* **Target Variable (y)**: Binary indicator of whether the client subscribed.

### Key Analytical Insights
* **Subscription Rate**: Significant class imbalance (**11.5%** Yes vs. **88.5%** No).
* **Call Duration**: Strongest success predictor (correlation: **+0.41**). Longer conversations lead to higher conversions.
* **Demographics**: Highest engagement found in the **30–40** age bracket; most clients are married with secondary education.
* **Financial Profile**: ~50% of clients have housing loans; only 1.8% have credit in default.
* **Campaign Timing**: Peak activity occurred in **May, August, and October**.

---

## 2. Technical Implementation
The analysis utilizes the standard Python Data Science stack to process data and handle exceptions.

### Core Libraries
* **NumPy**: Numerical operations and array handling.
* **Pandas**: Data cleaning, transformation, and DataFrame manipulation.
* **Matplotlib & Seaborn**: Statistical visualizations (histograms, bar charts, heatmaps).

### Methodology
1.  **Data Integration**: Loading the 45,211-row dataset using Pandas.
2.  **Exploratory Analysis**: Visualizing distributions for age, job types, and education.
3.  **Correlation Mapping**: Calculating relationships between features and the target variable to isolate key predictors.
4.  **Insight Synthesis**: Identifying previous campaign success and call duration as critical factors for targeting.

---

## Repository Structure

| Folder | File Name | Description |
| :--- | :--- | :--- |
| **Program** | `banking_data.csv` | Primary dataset. |
| | `script.ipynb` | Jupyter Notebook with EDA and visualization. |
| **Notes** | `Python Libraries.pdf` | Documentation on NumPy, Pandas, and Seaborn. |
| **Certificate**| `certificate.pdf` | Program completion document. |
| **Root** | `Presentation.pdf` | Final slide deck and stakeholder insights. |

---
