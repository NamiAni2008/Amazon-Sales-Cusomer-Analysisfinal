 

📌 Overview

This project analyzes Amazon sales data to gain deep insights into customer behavior, product performance, and operational efficiency.
Through data cleaning, exploratory data analysis (EDA), and visualization, we identify trends, seasonality, and patterns that can help businesses optimize sales strategies and improve customer experience.

⸻

🎯 Objectives
	•	🏷️ Understand Sales Trends – Identify monthly/seasonal demand fluctuations
	•	📦 Analyze Product Categories – Find top-selling categories and SKUs
	•	🛒 Study Customer Purchase Behavior – Quantity patterns, order values
	•	🚚 Evaluate Fulfillment & Logistics – Detect delivery/cancellation trends
	•	💡 Generate Business Insights – Recommend strategies for growth

⸻

🗂️ Dataset

The dataset includes:
	•	Order Details: Order ID, Date, Status, Fulfillment, Sales Channel
	•	Product Info: Category, SKU, Size, Style
	•	Shipping Info: Ship City, State, Postal Code, Country, Service Level
	•	Financial Data: Quantity, Currency, Amount

Source: Amazon Sales Report Dataset (Kaggle)

⸻

🔧 Project Workflow
	1.	Data Cleaning & Preparation
	•	Handled missing values (shipcity, shipstate, shippostalcode, shipcountry)
	•	Removed duplicate records
	•	Converted date columns to datetime format
	2.	Exploratory Data Analysis (EDA)
	•	Univariate Analysis: Order status distribution, sales amount distribution, monthly seasonality
	•	Bivariate Analysis: State-wise sales, category vs amount
	•	Multivariate Analysis: Correlation heatmap, pivot tables
	3.	Visualizations
	•	✅ Bar Charts (Top Categories, Monthly Orders)
	•	✅ Pie Chart (Sales Channel Contribution)
	•	✅ Box Plot (Quantity Ordered, Outliers Detection)
	•	✅ Correlation Heatmap (Relationship between numerical features)
	•	✅ Distribution Plots (Sales Amount)

⸻

📊 Key Insights
	•	🔼 High Volume in Apparel Categories – Kurta and Sets dominate total orders
	•	🗓️ Seasonality Observed – Sales peak during April and gradually decline in later months
	•	📉 Cancellation Trends – Cancelled/returned orders form a significant percentage and need attention
	•	🚚 Logistics Optimization – Most orders are shipped but “delayed/returned” statuses suggest areas for improvement
	•	💰 Revenue Driven by Low to Mid-Value Orders – Few high-value orders contribute disproportionately to revenue

⸻

💡 Recommendations
	•	Promotional Campaigns during peak sales months to maximize revenue
	•	Focus on Best-Selling Categories (Kurta, Sets, Western Dresses) for inventory stocking
	•	Reduce Returns & Cancellations by improving quality control and delivery accuracy
	•	Leverage Customer Insights to introduce cross-selling & upselling opportunities
	•	Monitor Logistics Performance to minimize delays and improve customer satisfaction

│
├── data/               # Dataset (raw & cleaned)
├── notebooks/          # Jupyter Notebooks with EDA & Visualizations
├── images/             # Saved plots & charts
├── reports/            # PDF / Documentation of findings
└── README.md           # Project Documentation
 🛠️ Tech Stack
	•	Language: Python 🐍
	•	Libraries: Pandas, NumPy, Matplotlib, Seaborn
	•	Environment: Jupyter Notebook
