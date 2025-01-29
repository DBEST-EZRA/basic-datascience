# US Population Data Analysis

This repository contains an analysis of US state population data from 2010 to 2019. The dataset is processed, cleaned, and visualized using Python.

## 📌 Assignment Overview

### **Problem 1: Merging and Cleaning Data**
- Merged two datasets (`population_even.csv` and `population_odd.csv`) using `STATE` and `NAME` as keys.
- Cleaned the data by:
  - Removing duplicate state columns.
  - Renaming columns to only contain the year.
  - Reordering columns in chronological order.
  - Handling missing values by averaging surrounding years.

### **Problem 2: Aggregating Population Data**
- Computed **maximum population** for each state across all years.
- Calculated **total population** across all years for each state.
- Determined the **total US population** for a single year.

### **Problem 3: Population Trends Visualization**
- Transformed the dataset from **wide format** to **long format** for time-series analysis.
- Created a **line plot** to show population trends over time for selected states using `seaborn`.

## 🚀 Technologies Used
- **Python**
- `pandas` for data manipulation.
- `matplotlib` & `seaborn` for visualization.

## 📊 How to Run the Code
1. Clone the repository:
   ```sh
   git clone https://github.com/DBEST-EZRA/basic-datascience.git
   cd us-population-analysis
