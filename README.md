🪔 Diwali Sales Data Analysis using Python
📋 Project Overview

This project performs Exploratory Data Analysis (EDA) on Diwali Sales data using Python.
The objective is to analyze customer purchase behavior during the Diwali season and identify factors influencing sales — such as gender, age group, marital status, state, occupation, and product categories.

📊 Dataset Information

File name: Diwali Sales Data.csv
Total records: 11,251
Columns: 15 (after cleaning → 13 usable columns)

Key Columns:
Column	Description
User_ID	Unique ID for each customer
Cust_name	Customer Name
Product_ID	Product Identifier
Gender	Gender of Customer
Age Group	Age group category
Age	Exact age
Marital_Status	0 = Unmarried, 1 = Married
State	State of residence
Zone	Regional Zone
Occupation	Job category
Product_Category	Type of product purchased
Orders	Number of orders
Amount	Total purchase amount
🧹 Data Cleaning

Removed irrelevant columns – Status, unnamed1

Handled missing values – Dropped rows with null Amount values

Changed data types – Converted Amount to integer

Renamed columns – Example: Marital_Status → Shaadi (optional rename)

🧠 Exploratory Data Analysis (EDA)
1. Gender Analysis

Most buyers are female.

Females also have a higher total purchase amount compared to males.

2. Age Group Analysis

Major buyers belong to the 26–35 years age group.

Most of them are female.

3. State Analysis

Top states by number of orders and total amount:

Uttar Pradesh

Maharashtra

Karnataka

4. Marital Status

Most buyers are married women.

They have higher purchasing power than unmarried customers.

5. Occupation

Top spending customers work in:

IT Sector

Healthcare

Aviation

6. Product Category

Most sold product categories:

Food

Clothing

Electronics

7. Top 10 Sold Products

Identified using highest order counts per Product_ID.

🧾 Key Insights / Conclusion

🎯 Conclusion:

Married women aged 26–35 years, from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, or Aviation, are the major buyers during the Diwali festival.
They primarily purchase Food, Clothing, and Electronics items.

🛠️ Technologies Used

Python 3.x

Libraries:

pandas → Data manipulation

numpy → Numerical computations

matplotlib & seaborn → Data visualization

📈 Visualizations

The following charts are included:

Gender vs Count

Gender vs Total Sales

Age Group vs Gender

State-wise Orders and Sales

Marital Status vs Amount (by Gender)

Occupation vs Sales

Product Category vs Sales

Top 10 Products by Orders

📂 Folder Structure
Diwali_Sales_Analysis/
│
├── Diwali Sales Data.csv
├── Diwali_Sales_Analysis.ipynb
├── README.md
└── visuals/              # (optional folder for graphs)

🚀 How to Run the Project

Clone this repository

git clone https://github.com/yourusername/Diwali-Sales-Analysis.git
cd Diwali-Sales-Analysis


Install dependencies

pip install pandas numpy matplotlib seaborn


Run the Jupyter Notebook

jupyter notebook Diwali_Sales_Analysis.ipynb

💡 Future Improvements

Add machine learning models to predict customer purchase trends.

Build a dashboard using Power BI or Streamlit for interactive insights.

Perform time-series analysis if date data becomes available.


]
📍 Location: India
