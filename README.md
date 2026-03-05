# E-Commerce Data Analysis & Business Insights


## 📌 Project Overview


This project performs an in-depth Exploratory Data Analysis (EDA) on a retail e-commerce dataset (Superstore Data). The goal is to uncover actionable business insights regarding sales trends, profitability across different product hierarchies, and customer segmentation to drive data-informed decision-making.

## 📊 Key Business Questions Addressed


### I utilized Python and interactive visualization libraries to solve the following business challenges:

1- Temporal Trends: Identified monthly sales and profit cycles to determine peak performance periods.

2- Product Analytics: Analyzed sales and profit margins across various Categories and Sub-categories.

3- Customer Segmentation: Evaluated how different segments (Consumer, Corporate, Home Office) contribute to the bottom line.

4- Efficiency Metrics: Calculated Sales-to-Profit ratios to identify high-margin business areas.

## 🛠️ Tech Stack


Language: Python

Data Manipulation: pandas

Visualization: Plotly (Express & Graph Objects), Matplotlib

Environment: Jupyter Notebook / VS Code

## 📈 Visualizations Included


To make the data easy to digest, I implemented:

1- Line Charts: To track monthly sales and profit volatility over time.

2- Bar Charts: For comparative analysis of sales/profit by Customer Segment and Category.

3- Pie Charts: To visualize the market share of specific product categories.

### 🚀 How to Run the Project
**1- Clone the repository:**

Bash


`git clone https://github.com/Rishita73/E-Commerce-EDA-Analysis.git`

**2- Install dependencies:**

Bash


`pip install -r requirements.txt`

**3- Open the Notebook: Run `e-commerce project.ipynb` in your preferred Jupyter environment.**

## 📈 Key Visualizations & Insights
### 1. Market Share by Category
**The analysis shows that Technology is the dominant category, accounting for 36.4% of total sales.**


<img width="2233" height="703" alt="Screenshot 2026-03-05 230629" src="https://github.com/user-attachments/assets/a42c56a3-0213-4d15-a6b1-cfe8a38bf3cd" />


### 2. Sales & Profit by Customer Segment
**Using Plotly Bar Charts, I identified that the Consumer segment is the largest contributor to the bottom line, significantly outperforming Corporate and Home Office segments in both volume and margin.**


<img width="1949" height="652" alt="Screenshot 2026-03-05 205544" src="https://github.com/user-attachments/assets/04baac11-6fe8-4bf4-991f-243ac1d5724d" />


### 3. Sub-Category Performance
**A detailed breakdown reveals that Phones and Chairs are the top-selling items, whereas some categories show high sales but lower-than-expected profit ratios.**


<img width="2246" height="727" alt="Screenshot 2026-03-05 230641" src="https://github.com/user-attachments/assets/40bdd426-777e-40e8-9174-9bed2290da3f" />


## 🎯 Project Conclusion & Learning Outcomes

### This project served as a comprehensive deep dive into the Exploratory Data Analysis (EDA) phase of the Data Science lifecycle. 

**1-Data Cleaning & Preprocessing:** I learned the critical importance of handling data encoding (using latin-1) and ensuring proper data types, such as converting date strings into datetime objects for accurate trend analysis.

**2-Decoding Business KPIs:** Beyond just writing code, I learned how to identify and calculate key metrics like Sales-to-Profit ratios, which are vital for assessing the health of any e-commerce operation.

**3-Interpreting Categorical Relationships:** Through the use of Plotly donut and bar charts, I discovered that while Furniture generates high sales, it doesn't always yield the highest profit. This taught me that volume does not equal value—a fundamental lesson in business intelligence.

**4-Identifying Seasonal Patterns:** By analyzing monthly sales cycles, I gained experience in identifying seasonality, which is a prerequisite for building reliable Predictive Models later in my career.

**5-Communicating Insights:** This project improved my ability to present complex data in a clear, visual format (Pie, Bar, and Line charts), making technical findings accessible to non-technical stakeholders.
