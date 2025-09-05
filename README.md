🖥️ Data Engineering Challenge – Slooze AI
📌 Introduction

This project focuses on collecting, cleaning, and analyzing laptop product data from Alibaba. Using Python (pandas, matplotlib, seaborn, regex), the raw data was transformed into meaningful insights, supporting market research, trend analysis, and business decision-making.

📊 Data Collection

Source: Alibaba product listings

Method: Web scraping tool Thunderbit

Extracted attributes:

Product Name

Product URL

Product Image

Price

Rating

Location

Product Type

🛠️ Data Cleaning & Preprocessing

The raw dataset was standardized and prepared for analysis:

Normalized column names.

Converted Price and Rating fields into numeric types.

Handled missing data (e.g., 13 missing ratings).

Removed duplicate URLs and rows.

Extracted keywords from product names for classification.

Binned prices into ranges:

0–10k, 10k–20k, 20k–50k, 50k–100k, 100k–500k, 500k+

📈 Analysis & Insights

The script generates key insights, including:

Summary Statistics

Total products: 117

Distinct product types: 11

Average price: ~25,189

Median price: 20,000

Min price: 1,290

Max price: 147,500

Top Product Types

Gaming Laptops (26)

Business Laptops (20)

Student Laptops (16)

Others (15)

Price Range Distribution

0–10k: 27 products

10k–20k: 32 products

20k–50k: 47 products

50k–100k: 8 products

100k–500k: 3 products

Keyword Frequency in Product Names

Most frequent: laptop, inch, ssd, intel, ram, business

Anomalies Detected

13 missing ratings

2 duplicate product URLs

No missing prices/images

📉 Visualizations

The notebook produces multiple plots (via matplotlib & seaborn):

Distribution of product types.

Price range counts.

Rating distributions.

Keyword frequency bar charts.

✅ Conclusion

This project demonstrates a complete data engineering pipeline:

Data scraping from Alibaba.

Cleaning & preprocessing with pandas.

Exploratory data analysis (EDA) with statistical summaries.

Visualization for insights.

The results provide a structured view of laptop offerings, useful for market analysis, competitor benchmarking, and strategic recommendations.
