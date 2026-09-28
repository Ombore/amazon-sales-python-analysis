 **Amazon Sales Data Analysis using Python**

 **Project Overview**

This project analyzes Amazon sales data using Python to understand sales performance, product performance, customer regions, pricing, payment methods, and revenue patterns. The project focuses on data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization to generate meaningful business insights.

 **Objectives**

- Clean and prepare the Amazon sales dataset for analysis.
- Analyze overall sales and revenue performance.
- Identify top-performing products.
- Compare revenue across customer regions.
- Analyze customer payment-method preferences.
- Examine discounted pricing patterns.
- Study the relationship between discounted price and total revenue.
- Create visualizations to communicate important findings.

 **Technologies Used**

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Google Colab

 **Dataset**

The project uses an Amazon sales dataset containing information related to products, pricing, revenue, customer regions, discounts, and payment methods.

 **Main Columns Analyzed**

- `product_id`
- `total_revenue`
- `customer_region`
- `discount_percent`
- `discounted_price`
- `payment_method`

 **Project Workflow**

 **1. Data Loading**

Loaded the Amazon sales dataset into a Pandas DataFrame and inspected its structure, dimensions, columns, and data types.

 **2. Data Cleaning**

Performed data cleaning and preparation by:

- Checking for missing values.
- Identifying and removing duplicate records.
- Checking unique values in categorical columns.
- Converting numerical columns to appropriate data types.
- Handling invalid numerical values using Pandas.

 **3. Exploratory Data Analysis**

Performed EDA to understand:

- Total revenue
- Average revenue
- Product performance
- Regional sales performance
- Discounted prices
- Payment methods
- High-revenue transactions
- Revenue distribution

 **4. Product Analysis**

Grouped sales data by `product_id` to identify products generating the highest total revenue.

 **5. Regional Analysis**

Analyzed `customer_region` to compare revenue performance across different regions and identify high-revenue regions.

 **6. Payment Method Analysis**

Analyzed payment methods to understand customer preferences and compare revenue generated through different payment methods.

 **7. Pricing and Revenue Analysis**

Examined the relationship between `discounted_price` and `total_revenue` using correlation analysis and scatter plots.

 **8. Data Visualization**

Created visualizations using Matplotlib and Seaborn, including:

- Revenue by customer region
- Top products by revenue
- Payment-method analysis
- Revenue distribution
- Discounted price distribution
- Discounted price vs. total revenue
- Correlation heatmap

 **Key Insights**

The analysis helped identify:

- Top-performing products based on revenue.
- Customer regions contributing higher revenue.
- Popular payment methods among customers.
- Differences in revenue and pricing patterns across regions.
- Relationships between numerical sales variables.
- Distribution of revenue and identification of high-revenue transactions.

 **Project Structure**

```text
amazon-sales-python-analysis/
│
├── Amazon_Sales_Analysis.ipynb
│
└── README.md
