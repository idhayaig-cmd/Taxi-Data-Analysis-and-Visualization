# 🚕 Taxi Data Analysis & Visualization

## 📌 Project Overview

This project analyzes taxi trip data using Python data analysis and visualization techniques.

The objective is to clean and explore taxi data, understand fare and distance patterns, examine payment behavior, and identify relationships among important numerical variables.

The project uses:

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🎯 Problem Statement

Taxi services generate large amounts of trip data every day. Raw trip data may contain missing values and can be difficult to interpret directly.

This project applies data-cleaning, exploratory-analysis, and visualization techniques to explore:

- Fare trends over time.
- Total fare by pickup borough.
- Payment-method distribution.
- Trip-distance distribution.
- Tip distribution by borough.
- Trip volume by pickup borough.
- Relationship between trip distance and fare.
- Correlation among distance, fare, tip, tolls, and total fare.
- Pairwise relationships among numerical variables.
- Fare distribution by payment method.

---

## 🛠️ Tools and Technologies

| Tool / Library | Purpose |
|---|---|
| Python | Data analysis and visualization |
| Pandas | Data loading, cleaning, grouping, and aggregation |
| Matplotlib | Line, bar, pie, histogram, and box plots |
| Seaborn | Statistical and categorical visualizations |
| Jupyter Notebook | Interactive analysis and documentation |

---

## 📂 Project Structure

```text
Taxi-Data-Visualization/
│
├── README.md
├── taxi_data_analysis.ipynb
├── summary_analysis.png
│
└── plots/
    ├── 01_fare_over_time.png
    ├── 02_total_fare_by_pickup_borough.png
    ├── 03_payment_method_distribution.png
    ├── 04_trip_distance_distribution.png
    ├── 05_tip_distribution_by_borough.png
    ├── 06_trip_count_by_pickup_borough.png
    ├── 07_distance_vs_fare_scatter.png
    ├── 08_correlation_heatmap.png
    ├── 09_pair_plot.png
    ├── 10_pair_plot_by_pickup_zone.png
    └── 11_fare_distribution_by_payment_method.png
```
---

## 🧹 Data Preparation

The following data-cleaning steps were performed:

- Checked the dataset for missing values.
- Identified columns containing missing values.
- Imputed numerical missing values using suitable statistical values.
- Used the mean or median for numerical columns where appropriate.
- Used the mode for categorical columns where appropriate.
- Removed rows when critical missing values could not be reasonably imputed.
- Converted the pickup timestamp column to datetime format.
- Selected relevant numerical and categorical columns.
- Prepared the data for grouping, aggregation, and visualization.

---
## 🔍 Key Findings

### Geographic Analysis

- Manhattan has the highest trip volume.
- Manhattan also generates the highest total fare.
- Trip activity and fare contribution are not evenly distributed across boroughs.

### Fare Analysis

- Fare values fluctuate over time.
- Fare has a strong positive relationship with distance.
- Fare and total fare have a very strong correlation.

### Distance Analysis

- Most trips are short-distance trips.
- The trip-distance distribution is right-skewed.
- Longer trips are less frequent but are associated with higher fares.

### Payment Analysis

- Credit card is the dominant payment method at 71.83%.
- Cash represents 28.17% of the displayed trips.
- Fare distributions can be compared across payment methods using a violin plot.

### Tip Analysis

- Tips are generally concentrated at lower values.
- The box plot reveals several higher-value tip outliers.
- Tip has a moderate positive relationship with total fare.

---

## 💡 Business Insights

- Manhattan may require the greatest number of available taxis because it has the highest trip volume.
- Long-distance trips are important contributors to total fare revenue.
- Digital-payment adoption is high in the analyzed dataset.
- High-value fare and tip outliers should be investigated for possible airport trips, unusual routes, or data-entry issues.
- Borough-level analysis can support driver allocation and operational planning.
- Fare and distance variables may be useful features for future fare-prediction models.

---

## 🧠 Skills Demonstrated

### Data Analysis

- Missing-value detection.
- Missing-value imputation.
- Datetime conversion.
- Data filtering and selection.
- GroupBy operations.
- Aggregation using `sum()` and `count()`.
- Correlation analysis.
- Distribution analysis.
- Outlier identification.

### Data Visualization

- Line chart.
- Bar chart.
- Pie chart.
- Histogram.
- Box plot.
- Count plot.
- Scatter plot.
- Heatmap.
- Pair plot.
- Violin plot.
- Hue-based categorical comparison.

### Analytical Thinking

- Trend analysis.
- Comparative analysis.
- Distribution analysis.
- Borough-level analysis.
- Payment-method analysis.
- Relationship analysis.
- Outlier identification.
- Business-oriented interpretation.

---

## 🏁 Conclusion

This project provides a clear overview of taxi trip behavior using Python-based data analysis and visualization.

The analysis shows that Manhattan is the dominant pickup borough by trip volume and total fare. Most trips are relatively short, while longer trips are associated with higher fares. Credit-card payments dominate the displayed transactions, and the correlation analysis confirms strong relationships among distance, fare, and total trip value.

---

## 👤 Author

**Idaya Gracy**

Aspiring Data Analyst


