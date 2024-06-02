# **Narendra Patil**

Aspiring Data Analyst | Core Skills: Statistical Analysis, Problem Solving, Communication, Critical Thinking, Attention to Detail | Certified in Python, SQL, AI | Proficient in Python, SQL, Tableau, Power BI

- LinkedIn : https://www.linkedin.com/in/narendra-patil-583b242a1/
- Github : https://github.com/Narendraspatil
- Kaggle : https://www.kaggle.com/narendraspatil
- Instagram : https://www.instagram.com/visionindata/

==============================================================
# Data Analysis of Myntra Products: Optimizing Pricing and Discount Strategies

### **Project Overview**

This project focuses on performing Exploratory Data Analysis (EDA) on a dataset of products from Myntra, an online ecommerce store, to derive meaningful insights and visualize them effectively. The primary goal is to optimize Myntra's pricing and discount strategies to increase sales, enhance customer satisfaction, and maintain profitability.

### **Problem Statement**

Myntra aims to balance competitive pricing with attractive discounts across diverse product categories. The challenge is to identify optimal pricing segments and understand customer preferences to refine pricing and promotional strategies.

### **Objectives**
1. Analyze the distribution of product prices and ratings.
2. Identify high-performing products and top sellers.
3. Examine the impact of pricing and discounts on customer ratings.
4. Provide actionable recommendations for pricing and discount strategies.

### **Technologies Used**
- Excel: For initial data understanding and basic data cleaning (although the large dataset required transitioning to Python for efficiency).
- Python: Data cleaning, Exploratory Data Analysis (EDA)
- Pandas: Data manipulation and analysis
- Matplotlib and Seaborn: Data visualization
- Power BI: Dashboard creation and data presentation

### **Data Cleaning Steps**
- Dropping unnecessary columns: Removed 'img', 'asin', and 'purl' columns.
- Checking for missing values: Ensured no missing values in the dataset.
- Checking for duplicates: Removed any duplicate entries.
- Creating new columns: Added 'totalDiscount' and 'percentageDiscount' columns to analyze discounts.

### **Key Analysis Points**

Statistical Analysis
- Price Distribution: Most products are priced between INR 150 to INR 8,000, with a concentration in the INR 400 to INR 1,100 range.
- Rating Distribution: Most products have ratings between 3.5 and 5, indicating overall positive customer sentiment.

Key Insights
- Mid-Range Focus: Myntra's product catalogue is predominantly mid-range, appealing to value-conscious customers.
- High Ratings for Mid-Range Products: Products below INR 20,000 receive higher ratings, suggesting good value perception.
- Discount Patterns: Higher-priced products receive larger absolute discounts, but percentage discounts are more variable for lower-priced items.

Relationship Analysis
- Price vs. Rating: Higher ratings are concentrated in products below INR 20,000.
- Price vs. Total Discount: Positive correlation, with higher-priced products receiving larger absolute discounts.
- Price vs. Percentage Discount: Wider spread for lower-priced items, more consistent for higher-priced products.

**Recommendations**
- Optimize Mid-Range Pricing: Maintain competitive pricing and attractive discounts for mid-range products to boost sales and customer satisfaction.
- Controlled Premium Discounts: Apply a consistent, conservative discount strategy for premium products to maintain brand perception and profitability.
- Dynamic Discounting: Implement dynamic discounting strategies for budget-friendly products based on seasonality and inventory levels.

### **Conclusion**

This analysis provides a strategic approach for Myntra to refine its pricing and promotional strategies. By focusing on mid-range products with competitive discounts and maintaining premium segments with controlled discounting practices, Myntra can optimize revenue, profitability, and customer satisfaction across different product categories.

### **Dashboard**

A Power BI dashboard was created to visualize the insights from the analysis, featuring:
- Distribution of Ratings by Products
- Distribution of Prices of Products
- Average Price, Median Price, and Total Number of Products
- Top Rated Products, Most Expensive Products, Most Discounted Products
- Top Listed Products and Top Sellers
- Link to Power BI Dashboard

### **How to Run the Project**
- Clone the repository.
- Install the necessary libraries from requirements.txt.
- Run the Jupyter notebooks to perform the EDA.
- Open the Power BI file to explore the dashboard.
