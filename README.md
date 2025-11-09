Flipkart Product Sales Analysis using Web Scraping & EDA

This project extracts product listings (Mobiles, Laptops, Tablets) from Flipkart using Python web scraping, cleans the collected data, and performs Exploratory Data Analysis (EDA) to uncover pricing patterns, brand performance, and customer satisfaction insights.

This repository showcases end-to-end data analysis starting from raw web data → structured dataset → meaningful visual insights.
Problem Statement

Flipkart hosts thousands of products with varying prices, specifications, and seller listings. Understanding:

How RAM, storage, processor, and brand affect pricing,

Which products deliver better customer satisfaction,

Which categories dominate sales popularity,
is difficult without structured analysis.

This project solves that by:

✅ Scraping raw HTML data from Flipkart
✅ Cleaning messy, inconsistent product attributes
✅ Structuring data into CSV format
✅ Analyzing price, rating, brand, and specification trends
✅ Building insights useful for buyers & businesses
Category	Tools / Libraries
Language :	Python
Web Scraping : Requests, BeautifulSoup
Data Cleaning : Pandas, NumPy
Visualization : 	Matplotlib, Seaborn
Documentation	Jupyter Notebook
Key Insights
📌 1. Price Distribution

Most products fall between ₹10,000 – ₹50,000, indicating high demand in the mid-range segment.

📌 2. Ratings

Majority of ratings fall between 4.0 – 4.7, showing strong customer satisfaction.

📌 3. Brand Performance

Brands like HP, Dell, Lenovo, Samsung, Redmi dominate product listings.

📌 4. RAM & Price Relationship

Higher RAM values strongly correlate with higher pricing across categories.

📌 5. Tablets Have Highest Ratings

Tablets consistently achieve the best average customer ratings, followed by mobiles and laptops.
Visualizations Included

Price Distribution

Rating Distribution

Average Rating by Category

Price vs RAM (Scatter Plot)

Processor Count Distribution

Category-wise Price Boxplots

Multivariate Pairplot
