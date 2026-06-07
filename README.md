## Book Sales EDA Analysis


## Project Overview

This project performs Exploratory Data Analysis (EDA) on a book sales dataset to uncover trends, patterns, and factors influencing book sales performance. The analysis focuses on understanding relationships between sales, pricing, ratings, authors, genres, and publishing years through data visualization and statistical exploration.

The objective of this project is to transform raw book sales data into actionable business insights that can help publishers, retailers, and authors make data-driven decisions.


##Dataset Information

The dataset contains information related to books, including:

- Book Title
- Author
- Genre
- Language
- Publishing Year
- Sale Price
- Units Sold
- Gross Sales
- Book Ratings
- Rating Count

The dataset was analyzed to identify sales trends, top-performing authors, popular genres, pricing patterns, and customer engagement metrics


##Data Cleaning Steps

The following data preprocessing and cleaning steps were performed:

- Removed duplicate records.
- Checked and handled missing values.
- Corrected data types for numerical and categorical columns.
- Standardized column names for consistency.
- Removed unnecessary columns that were not useful for analysis.
- Verified data quality and ensured accurate formatting for EDA.
- Prepared the dataset for visualization and statistical analysis.


## Key Findings

- A small number of authors contribute a large share of total book sales.
- Book sales show noticeable variation across publishing years.
- Sale price and units sold exhibit measurable relationships that influence revenue generation.
- Certain genres consistently receive higher reader engagement and ratings.
- Correlation analysis highlights the strongest relationships among sales, pricing, ratings, and revenue-related variables.


## Visualization
- Top Authors by Gross Sales
- Units Sold by Publishing Year
- Sale Price vs Units Sold
- Genre vs Ratings Count
- Language_distribution
- Co-Relation Heatmap


## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code


## Project Structure
EDA-Book-Sales-Pipeline/
│
├── data/
│   ├── Books_Data_Clean.csv
│
├── notebooks/
│   └── Book_Sales.ipynb
│
├── screenshots/
│   ├── top_authors_sales.png
│   ├── units_sold_by_year.png
│   ├── sale_price_vs_units_sold.png
│   ├── genre_vs_ratings.png
│   ├── correlation_heatmap.png
|   ├── language_distribution.png 
│
├── README.md
├── requirements.txt
└── .gitignore



