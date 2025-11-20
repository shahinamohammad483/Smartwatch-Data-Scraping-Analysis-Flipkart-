⌚ Smartwatch Market Analysis – Flipkart Web Scraping & EDA

This project performs a complete data analysis workflow on smartwatch listings from Flipkart.
It covers every stage—from web scraping raw HTML data to cleaning, transforming, analyzing, and presenting insights for business decision-making.

🎯 Project Objectives

- Collect smartwatch product data from Flipkart using web scraping

- Clean and standardize unstructured e-commerce data

- Perform Exploratory Data Analysis (EDA) to identify key trends

- Understand pricing strategies, discount behavior, and brand dominance

- Build insights to support business decisions and customer comparison

📂 Included Files

1️⃣ Web Scraping Script 

Scrapes smartwatch product details such as:

- Brand & model
- MRP, selling price, discount %
- Deal type
- Display size
- Watch size
- Additional metadata

Tools Used:
Python, Requests, BeautifulSoup, Pandas

2️⃣ Cleaned Dataset — cleaned_smartwatch_data.csv

A structured dataset created after:

- Converting prices/MRP to numeric
- Standardizing watch sizes
- Converting display size (mm → inches)
- Cleaning deal type text
- Creating engineered fields
- Removing duplicates & fixing null values

3️⃣ Jupyter Notebook — data_cleaning_and_analysis.ipynb

Includes:

 Data Cleaning
 
- Cleaning text, numbers, categories
- Handling missing values
- Standardizing measurement units
- Correcting inconsistent formats

Feature Engineering

- Discount Amount
- Discount Category (Low, Medium, High, Very High)
- Price Category (Budget → Luxury)
- Display Size (inch conversion)

EDA

- Univariate, Bivariate & Multivariate analysis
- Price trends across brands
- Discount vs Price behavior
- Deal type effectiveness
- Size category distribution
- MRP vs Price correlation


🛠 Tech Stack

- Python 3.10+
- BeautifulSoup4 – Web Scraping
- Requests – HTTP Requests
- Pandas, NumPy – Cleaning & Analysis
- Matplotlib, Seaborn – Visualizations
- Jupyter Notebook – EDA Workflow
- PowerPoint – Presentation
