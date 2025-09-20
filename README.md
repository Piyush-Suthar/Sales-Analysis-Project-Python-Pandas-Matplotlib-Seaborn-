**# Sales Analysis Project – Python (Pandas, Matplotlib, Seaborn)**

📌 **Project Overview**

      This project performs a comprehensive Retail Sales Analysis using Python, with pandas for data manipulation and matplotlib/seaborn for visualization.
      The analysis helps businesses understand sales trends, customer behavior, product preferences, and profitability across regions, genders, age groups, and product   categories.

📂 **Dataset Information**

      File: data_sales.xlsx

      Key Columns:

      Date → Transaction date

      Country / State → Customer location

      Customer_Gender → Customer gender

      Customer_Age → Customer age

      Product_Category / Sub_Category → Product classification

      Unit_Price, Unit_Cost, Order_Quantity → Sales & profit computation

      Total_Sales → Calculated as Unit_Price * Order_Quantity

      Profit_Margin_% → Calculated as ((Unit_Price - Unit_Cost) / Unit_Price) * 100

🔧 **Steps Performed**
1️⃣ **Data Loading & Preprocessing**

      Loaded Excel file using pd.read_excel()

      Checked data types and null values (df.info() & df.isnull().sum())

      Checked for duplicate or repeated values in Country

      Added Total_Sales column (Unit_Price * Order_Quantity)

      Converted Date column to datetime format and extracted Year

2️⃣ **Sales Analysis**

      State-wise Sales: Top 5 states by total sales (bar chart)

      Country-wise Sales: Top 5 countries by total sales (bar chart)

      Gender-wise Contribution: Pie chart of sales by customer gender

      Yearly Sales Trend: Line chart of total sales by year

      Product Category Popularity: Top product category per country (bar chart)

3️⃣ **Customer Analysis**

      Age Group Analysis:

      Created age groups (0-17, 18-29, 30-44, 45-59, 60+)

      Analyzed sales per age group (bar chart)

      Product Preferences by Age Group:

      Grouped by Age_Group and Product_Category

      Visualized order quantities (bar chart)

      Gender Distribution per Product Category:

      Grouped and visualized customer gender per product category (bar chart)

4️⃣ **Profit & Margin Analysis**

      Calculated profit margin % per product

      Aggregated average profit margin by product category

      Visualized profit margins (bar chart)

5️⃣ **Time Series & Trends**

      Analyzed sales trend over time (line plot)

      Aggregated monthly, yearly, and daily sales

      Observed peak and lowest sales periods

6️⃣ **Frequency & Distribution Analysis**

      Frequency distribution of Country, Customer_Gender, Product_Category, Sub_Category

      Frequency of sub-categories within major categories (Accessories, Bikes, Clothing)

      Age group distribution using pd.cut() and seaborn countplot

7️⃣ **Aggregation & Insights**

      Aggregate sales:

      By Country

      By Product Category

      By Customer Gender

      By Country & Product Category

      Average Sales & Customer Age: Aggregated by Product Category

      Gender Distribution within Product Categories: Visualized with grouped bar charts

📊 **Key Visualizations**

      Top States & Countries by Sales

      Gender Contribution (Pie Chart)

      Monthly & Yearly Sales Trends (Line Charts)

      Top Product Category by Country

      Product Preferences by Age Group

      Average Profit Margin per Product Category

      Frequency Distribution of Age Groups, Countries, Categories, and Sub-Categories

      Gender Distribution by Product Category

🛠️ **Tools & Libraries**

      Python 3.x

      Pandas → Data manipulation & aggregation

      NumPy → Numerical operations

      Matplotlib → Basic visualizations

      Seaborn → Statistical and advanced visualizations

🎯 **Insights Delivered**

      Identified top-performing states and countries in sales

      Observed gender-wise contribution and product preferences by age

      Analyzed profit margins per product category

      Detected trends in sales over time

      Determined popular sub-categories within major product categories

      Generated aggregated summaries for strategic business decisions
