# power-bi-ass
# E-Commerce Sales Data Analysis Using Power BI

## 📌 Project Overview

This project focuses on preparing, transforming, cleaning, and modeling e-commerce sales data using **Microsoft Power BI and Power Query Editor**. The goal is to create a reliable data model that supports business analysis and helps understand sales performance, profitability, and sales targets.

This project demonstrates practical data analytics skills, including data cleaning, data integration, aggregation, and relationship modeling.

## 🎯 Project Objectives

- Import multiple datasets into Power BI.
- Clean and transform data using Power Query Editor.
- Handle missing values and duplicate records.
- Create calculated and conditional columns.
- Merge related datasets using Order ID.
- Perform grouping, sorting, filtering, and aggregation.
- Establish relationships between tables.
- Prepare a structured data model for business analysis.

## 📂 Datasets

This project uses three datasets:

### 1. List of Orders
- Order ID
- Order Date
- Customer Name
- City
- State
- Category
- Amount
- Profit

### 2. Order Details
- Order ID
- Category
- Sub-Category
- Quantity
- Amount
- Profit

### 3. Sales Target
- Category
- Month of Order Date
- Target

## 🛠️ Tools and Technologies

- Microsoft Power BI
- Power Query Editor
- Data Cleaning and Transformation
- Data Modeling
- Data Aggregation
- GitHub

## 🔄 Data Preparation and Transformation

The following operations are included in the project:

1. Imported the three datasets into Power BI.
2. Limited the List of Orders table to the first 500 rows.
3. Changed column data types, including Order Date, Amount, and Target.
4. Standardized customer names using Proper Case.
5. Combined City and State into a Location column.
6. Created a Profit Margin column using Profit divided by Amount.
7. Created a Profit Status column to classify records as Profit, Loss, or Break-Even.
8. Merged List of Orders and Order Details using Order ID.
9. Identified and handled missing values and duplicate records.
10. Sorted orders by Order Date in descending order.
11. Filtered orders by state for regional analysis.

## 📊 Data Aggregation

The project includes the following aggregations:

- Count of Order ID
- Average Profit by Category
- Total Amount by Sub-Category
- Total Sales Target by Month

These aggregations help summarize sales performance across product categories and time periods.

## 🔗 Data Modeling

Relationships are established between the datasets using the relevant keys:

- List of Orders and Order Details using Order ID.
- Order Details and Sales Target using Category, as specified in the assignment.

Relationship cardinality and active status are checked in Power BI Model view.

## 📈 Expected Business Insights

The prepared data model can support analysis of:

- Sales performance by category and sub-category.
- Profitability and profit margins.
- Regional sales performance.
- Monthly sales targets.
- Loss-making and profitable orders.
- Sales performance against business targets.

*Actual findings and numerical results will be added after completing the analysis.*

## 📸 Project Screenshots

Screenshots of the following will be added to document the project:

- Power Query data cleaning and transformation.
- Merged Orders Data table.
- Aggregated tables.
- Power BI Model view and relationships.
- Final report visuals, if created.

## 📁 Repository Structure

```text
E-Commerce-Sales-Analysis/
│
├── README.md
├── Dataset/
│   ├── List of Orders.csv
│   ├── Order Details.csv
│   └── Sales Target.csv
├── PowerBI/
│   └── Ecommerce_Sales_Analysis.pbix
└── Screenshots/
    ├── PowerQuery.png
    ├── DataModel.png
    └── Report.png
```

## 🚀 Learning Outcomes

Through this project, I am developing practical skills in data preparation, data quality management, Power Query transformations, data aggregation, and relational data modeling using Power BI.

## 👨‍💻 About Me

I am a B.Com General student learning Data Analytics and building practical projects to develop my analytical and technical skills.

I am interested in using data to identify patterns, understand business performance, and support data-driven decision-making.

## 🏁 Conclusion

This project demonstrates an end-to-end data preparation and modeling workflow for e-commerce sales data using Power BI. It forms part of my Data Analytics learning journey and professional portfolio.
