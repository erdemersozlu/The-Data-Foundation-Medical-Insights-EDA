# 🩺 The Data Foundation: Heart Disease Insights
> **"Anchored to Data"** — *A meticulous Exploratory Data Analysis (EDA) on cardiovascular health records.*

## 📌 Overview
This project, **The Data Foundation**, is the first milestone of my data science journey. Inspired by Francesco's philosophy, I focused on mastering the "raw truth" of the data before building predictive models. Using a dataset of 1,025 patients, I performed rigorous cleaning and statistical analysis to uncover the key factors behind heart disease.

The goal was to transform a flat CSV file into a structured, visual, and model-ready "fuel" for the next stage: **The Linear Engine**.

## 📊 Dataset Structure
The project uses the `heart.csv` dataset, which contains 14 clinical features:
* **Demographics:** Age, Sex.
* **Clinical Data:** Chest Pain Type (cp), Resting Blood Pressure (trestbps), Cholesterol (chol), etc.
* **Target:** Heart Disease Diagnosis (0 = Healthy, 1 = Disease).

## 🛠️ Tech Stack
* **Python 3.x**
* **Pandas:** Data cleaning and structure validation.
* **Seaborn & Matplotlib:** Statistical visualizations and correlation heatmaps.
* **NumPy:** Mathematical summaries.

## 🔍 Key EDA Milestones

### 1. Data Check-up & Cleaning
* Verified 1,025 records with no missing values.
* Conducted structural analysis using `df.info()` and `df.shape`.
* Ensured data types are optimized for mathematical processing.

### 2. Statistical Visualization
* **Age Distribution:** Identified the core patient demographic through Histograms.
* **Health Correlations:** Discovered the inverse relationship between **Age** and **Max Heart Rate (thalach)** using Scatter Plots.
* **Comparative Analysis:** Used Boxplots to visualize how **Cholesterol** levels vary between healthy and diagnosed groups.

### 3. Preparation for Machine Learning
* Generated a comprehensive statistical summary with `df.describe().T`.
* Validated feature scales to determine the need for normalization in the upcoming **Linear Engine** phase.



## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/erdemersozlu/The-Data-Foundation-Medical-Insights-EDA
   ```
2. Install requirements:
   ```bash
   pip install pandas seaborn matplotlib
   ```
3. Run the analysis:
   ```bash
   jupyter notebook notebooks/EDA_Analysis.ipynb
   ```

## 📜 Conclusion
Mastering the foundation proved that data is not just numbers; By staying **anchored to data**, we've identified that factors like `thalach` and `cp` are crucial indicators. 



