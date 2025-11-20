✅ README File for Task 5 (Copy–Paste into README.md)
📊 Data Analysis on CSV Files — Task 5

This project performs basic sales data analysis using Pandas and Matplotlib.

✅ Features

Load CSV data using Pandas

Explore dataset (head, describe, shape)

Group sales by product/category

Calculate total revenue

Create bar charts for insights

📁 Dataset

A Kaggle-style dataset named sales.csv is included.

Columns:

Column	Meaning
OrderID	Unique order number
Product	Product purchased
Category	Type of product
Quantity	Number of units
Price	Price per unit
Total	Total amount (Quantity×Price)
Date	Date of purchase
▶️ How to Run

Upload sales.csv to Colab / Jupyter Notebook

Add the analysis code cell

Run all cells to generate insights and charts

📈 Skills Used

Pandas

DataFrame operations

groupby() and aggregation

Data filtering

Matplotlib visualizations

📝 Interview Concepts Covered

Pandas is used for data analysis and manipulation

DataFrame = table-like data structure

Read CSV → pd.read_csv()

groupby() → used for aggregation

Filter rows → df[df["col"] == value]

loc vs iloc

loc → label based

iloc → index based

.head() → first 5 rows

Bar chart → plt.bar()

.shape → number of rows × columns

NaN → missing value

📦 Repository Structure

task5-data-analysis/

│── sales.csv

│── notebook.ipynb

│── README.md
