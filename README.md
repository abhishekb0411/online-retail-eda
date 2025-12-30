# Online Retail Exploratory Data Analysis (Python)

## Project Overview
This project presents an end-to-end exploratory data analysis (EDA) of transactional data from an online retail store. The objective of the analysis is to uncover sales trends, customer purchasing behaviour, and product performance patterns that can support data-driven business decision-making in a retail context.

The analysis focuses on cleaning raw transaction data, engineering relevant features, and extracting actionable insights through descriptive statistics and visual exploration.

---

## Dataset
The project uses the publicly available **Online Retail** dataset, which contains transaction-level data from a UK-based online retail store covering the period **2010–2011**.

Each record represents a product-level purchase and includes information such as invoice number, product description, quantity, unit price, customer identifier, transaction timestamp, and country.

**Data source:**  
UCI Machine Learning Repository  
https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx

> Note: The dataset is not included in this repository and should be downloaded directly from the source link above.

---

## Tools and Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Analysis Workflow
The project follows a structured analytical workflow:

1. **Data Understanding and Exploration**
   - Dataset structure and schema inspection
   - Summary statistics and missing value analysis

2. **Data Cleaning and Preparation**
   - Removal of invalid transactions (negative quantities and prices)
   - Handling missing customer and product information
   - Deduplication of records

3. **Feature Engineering**
   - Creation of transaction-level revenue (`TotalSales`)
   - Extraction of time-based features (year, month, day, hour)

4. **Exploratory Data Analysis**
   - Overall revenue assessment
   - Monthly sales trend analysis
   - Top-performing products by revenue
   - High-value customer identification
   - Geographic revenue distribution

---

## Key Insights
- Sales exhibit clear **seasonal patterns**, with a strong revenue peak in the final quarter of the year.
- A relatively small subset of products contributes a **disproportionate share of total revenue**.
- Revenue is highly concentrated among a small group of **high-value customers**.
- The **United Kingdom** dominates sales, with secondary contributions from several European markets.

---

## Business Recommendations
- Prioritise inventory planning around consistently high-performing products, especially during peak seasonal periods.
- Develop targeted retention strategies for high-value customers through loyalty or personalised engagement initiatives.
- Scale operational and marketing efforts ahead of identified seasonal demand peaks.
- Explore targeted growth opportunities in secondary geographic markets beyond the UK.

---

## How to View the Project
Open the Jupyter Notebook file below to view the full analysis, code, and visualisations:

- `online_retail.ipynb`

## Author
Abhi
