# Laptop Data Cleaning & Visualization Project

## Project Overview

This project focuses on cleaning, preprocessing, analyzing, and visualizing a laptop dataset using Python data science libraries. The objective of the project is to transform raw and inconsistent data into meaningful insights through data analysis and visualization techniques.

The project demonstrates real-world data preprocessing workflows including handling missing values, removing duplicates, fixing inconsistent data formats, detecting outliers, and generating analytical visual reports.

---

## Objectives

* Handle missing and invalid values
* Remove duplicate records
* Detect and analyze outliers
* Convert and clean inconsistent data formats
* Perform exploratory data analysis (EDA)
* Generate visual insights using graphs and charts
* Build a clean and analysis-ready dataset

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## Data Cleaning Steps

* Removed unnecessary columns
* Handled missing values using row removal techniques
* Replaced invalid symbols such as `?` with null values
* Cleaned numerical columns like RAM and Weight
* Converted object datatypes into numerical datatypes
* Removed duplicate records
* Performed outlier analysis using boxplots and IQR methods

---

## Exploratory Data Analysis

The project includes:

* Price distribution analysis
* Laptop brand comparison
* RAM vs Price analysis
* Laptop type distribution
* Correlation heatmaps
* Average price analysis by company

---

## Key Insights

* High RAM laptops generally have higher prices
* Premium brands show significantly higher average pricing
* Gaming laptops tend to be heavier and more expensive
* Most laptops in the dataset contain 8GB RAM
* Certain outliers heavily affect price distribution

---

## Project Structure

* `laptopData.csv` → Raw dataset
* `cleaned_laptop_data.csv` → Processed dataset
* `notebook.ipynb` → Full analysis notebook
* `README.md` → Project documentation

---

## Future Improvements

* Build machine learning models for price prediction
* Create an interactive dashboard using Streamlit or Power BI
* Perform feature engineering for better insights
* Add advanced statistical analysis

---

## Conclusion

This project demonstrates a complete data preprocessing and visualization workflow commonly used in real-world data science projects. It highlights the importance of data cleaning, exploratory analysis, and insight generation in transforming raw datasets into valuable information.
