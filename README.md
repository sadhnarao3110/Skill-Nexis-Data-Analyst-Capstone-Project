# Skill Nexis – Data Analyst Course Final Capstone Project

## 📊 Project Overview

This repository contains my **Final Capstone Project** completed as part of the **Skill Nexis Data Analyst Course**.

The project focuses on end-to-end financial data analysis to identify sales trends, evaluate profitability, understand business performance, and generate actionable insights using data analytics tools and techniques.

The project covers data cleaning, exploratory data analysis, SQL-based analysis, Excel reporting, regression modeling, and data visualization, with Power BI dashboard development for interactive reporting.

## 🎯 Project Objectives

- Clean and preprocess the financial dataset.
- Perform exploratory data analysis (EDA).
- Analyze sales, profit, discounts, and units sold.
- Identify top-performing products, countries, and business segments.
- Analyze sales trends and profitability.
- Apply regression modeling to estimate sales.
- Create visualizations and an interactive Power BI dashboard.
- Communicate findings through a final project report.

## 🛠️ Tools and Technologies

- **Python** – Data cleaning, analysis, and modeling
- **Pandas and NumPy** – Data manipulation
- **Matplotlib and Seaborn** – Data visualization
- **Jupyter Notebook** – Analysis and experimentation
- **SQL** – Data querying and analysis
- **Microsoft Excel** – Data analysis and reporting
- **Power BI** – Dashboard development
- **Scikit-learn** – Regression modeling

## 📂 Dataset Information

The financial dataset contains **700 records and 16 original columns** related to sales, products, discounts, costs, and profits.

Key fields include:

- Country
- Segment
- Product
- Units Sold
- Manufacturing Price
- Sale Price
- Gross Sales
- Discounts
- Sales
- COGS
- Profit
- Date and time-related fields

The data was inspected and cleaned before being used for further analysis.

## 🔄 Project Workflow

### 1. Data Cleaning and Preprocessing
- Inspected data types and dataset structure.
- Checked for missing values and duplicate records.
- Standardized column names.
- Handled missing discount category values.
- Prepared the cleaned dataset for analysis.

### 2. Exploratory Data Analysis
- Evaluated overall sales and profitability.
- Compared performance across countries and products.
- Analyzed sales by business segment.
- Explored yearly sales trends.
- Examined discount patterns and business performance.

### 3. SQL and Excel Analysis
- Used SQL queries to summarize and analyze business data.
- Used Excel for tabular analysis, calculations, and reporting.

### 4. Regression Modeling
- Developed a linear regression model to estimate sales.
- Evaluated the model using MAE, RMSE, and R².
- Compared actual and predicted sales to understand model performance.

### 5. Data Visualization and Power BI
The dashboard design includes key performance indicators and visualizations for:

- Total Sales
- Total Profit
- Units Sold
- Total Discounts
- Profit Margin
- Country-wise sales
- Product-wise sales
- Segment-wise profit
- Interactive filters for exploring business performance

## 📈 Key Results

| Metric | Result |
|---|---:|
| Total Records | 700 |
| Total Sales | 118,726,350.26 |
| Total Profit | 16,893,702.26 |
| Overall Profit Margin | 14.23% |
| Top Country by Sales | United States of America |
| Top Product by Sales | Paseo |
| Top Segment by Sales | Government |

*Note: The dataset does not specify a currency, so monetary values are shown without a currency symbol.*

## 🤖 Regression Model Performance

| Evaluation Metric | Result |
|---|---:|
| MAE | 78,386.63 |
| RMSE | 109,673.34 |
| R² Score | 0.7828 |

The model achieved an R² score of approximately **78.28%** on the selected test split. This result reflects the model's performance on that split and should not be interpreted as a guarantee of future forecasting accuracy.

## 💡 Key Business Insights

- The United States of America generated the highest sales among the countries in the dataset.
- Paseo was the leading product by sales.
- The Government segment generated the highest sales among the segments.
- Profitability and discount patterns can help identify opportunities to improve business performance.
- Data visualization can help stakeholders monitor key metrics and make informed decisions.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install Python and the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn openpyxl jupyter joblib
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the project notebook.
5. Verify that the dataset path is correct.
6. Run the notebook cells in sequence.

SQL queries can be run in a compatible database after importing the dataset. Excel files can be opened in Microsoft Excel, and a completed `.pbix` file can be opened using Power BI Desktop.

## 📦 Project Deliverables

- Original financial dataset
- Cleaned dataset
- Python analysis notebook
- SQL queries
- Excel analysis workbook
- Regression model results
- Final project report in PDF format
- Power BI dashboard, once completed

## 🔮 Future Scope

- Improve sales forecasting with time-based validation.
- Compare multiple machine learning algorithms.
- Add more profitability and discount analysis.
- Enhance the Power BI dashboard with additional interactive reports.
- Automate data refresh and reporting.

## 👨‍💻 Author

**Sadhana Rao**

**Program:** Data Analyst Course  
**Training Organization:** Skill Nexis  
**Project:** Financial Data Analysis – Final Capstone Project

## 📄 Disclaimer

This project was completed for educational and portfolio purposes as part of the Skill Nexis Data Analyst Course. Dataset ownership and redistribution are subject to the original dataset's licensing terms.

