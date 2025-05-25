# 📊 Tata Neu Sales Dashboard

This Power BI project provides a **dynamic and interactive visualization** of key sales metrics across multiple years, tailored for **business leaders, sales analysts, and decision-makers**. It enables users to **monitor performance, uncover insights, and make data-driven decisions**.

---
## 📂 Data Sources & Structure
The dashboard integrates three Excel files:

### 1️⃣ Employee Information (`Employee_Information.xlsx`)
This dataset contains workforce details, including department assignments and salary information.

| Column Name | Description |
|------------|------------|
| Employee ID | Unique identifier for each employee |
| Name | First name of the employee |
| Last Name | Surname of the employee |
| Date of Birth | Employee's birth date (may need formatting adjustments) |
| Income | Salary information |
| Department | Employee's assigned department (Sales, Marketing, etc.) |
| Employee Name | Full name of the employee |

### 2️⃣ Product Information (`Product_Information.xlsx`)
Categorization and details of available products.

| Column Name | Description |
|------------|------------|
| Product ID | Unique identifier for each product |
| Category | Main classification (Furniture, Technology, Office Supplies) |
| SubCategory | Sub-classification (Tables, Cameras, Binders, etc.) |
| Product Name | Name of the product |

### 3️⃣ Sales Information (`Sales_Information.xlsx`)
Transaction details including revenue and customer data.

| Column Name | Description |
|------------|------------|
| Order ID | Unique identifier for each sales order |
| Order Date | Date when the order was placed |
| Customer Name | Name of the purchasing customer |
| Product ID | Identifier for the product being sold |
| Quantity | Number of units sold per transaction |
| Unit Price | Price per unit of the product |
| Total Sales | Revenue generated from each sale |

---

## 🎯 Dashboard Insights

**Purpose**: Overview of total metrics and high-level performance

**Visuals Used**:
- **KPI Cards**: Total Sales, Total Profit, Total Orders (with YoY % change)
- **Waterfall Chart**: Profit change by Product Category
- **Stacked Bar Chart**: Profit by Segment
- **Area & Line Chart**: Monthly Sales and Profit trend
- **Bar Chart**: Profit by Subcategory

**Filters/Slicers**:
- Year (2020–2023)
- Country
- Segment
- Product Category & Sub-Category

![image alt](https://github.com/Bhavani1989/TataNeuSkillDashboard/blob/6b428e56a6c05d35c8c26576d6a28b7aa48ef971/Sales_Dashboard.png)

## 🚀 Features

- **KPI Monitoring**: Real-time tracking of Total Sales, Total Profit, and Order Count with Year-over-Year (YoY) comparisons.
- **Profit Waterfall Analysis**: Visualizes contribution to profit changes by product category.
- **Segment Breakdown**: Understands profit distribution across customer segments—**Consumer, Corporate, and Home Office**.
- **Monthly Sales & Profit Trends**: Combined area and line charts reveal seasonal variations and sales momentum.
- **Subcategory Profit View**: Horizontal bar chart for detailed analysis of profit by product subcategory.
- **Interactive Filters & Slicers**:
  - Year slicer (2020 to 2023)
  - Region slicer
  - Country slicer
  - Category, Sub-Category, and Segment filters
  - Product- and Employee-level slicers
- **Multi-Page Navigation**:
  - Sales Information  
  - Top Countries and Products  
  - Sales Performance  
  - Employee Performance  
  - Product Information

---
## 🌍 Top Countries & Product Performance Dashboard
**Purpose**: Analyze sales and profits across countries and top-selling products

**Visuals Used**:
- **Map Visual**: Total Sales by Country
- **Stacked Column Chart**: Profit by Country and Category
- **Bar Chart**: Top 10 Products by Sales
- **Bar Chart**: Top 10 Products by Profit

**Filters/Slicers**:
- Year
- Region
- Product Category

This dashboard provides insights into **top profit-generating countries and high-performing products**.

#### Top 3 Countries by Profit  
- **India:** **711** profit  
- **Australia:** **665** profit  
- **Russia:** **494** profit  

#### Additional Country Profit Breakdown  
- **South Africa:** **154** profit  
- **Japan:** **57** profit  
- **Sweden:** **56** profit  

## 📊 Sales Performance Dashboard

**Purpose**: Compare year-over-year trends across different metrics

**Visuals Used**:
- **Line Chart**: YoY % Change in Sales
- **Column Chart**: Sales This Year vs Last Year by Category
- **Line Chart**: YoY % Change in Profit
- **Line Chart**: YoY % Change in Orders

**Filters/Slicers**:
- Year
- Country
- Category

This tab gives a detailed breakdown of yearly trends and category-level insights.

![image alt](https://github.com/Bhavani1989/TataNeuSkillDashboard/blob/f41f6a957c4e7d50cddbfc167ad4971920ad9779/Sales_performance.png)

### 📈 Visual Components

#### 1. **YoY % Change in Sales**
- Sales peaked at 156K in 2021 and dropped to 97K in 2023.
- Significant YoY declines: -18.92% (2022), -23.67% (2023)

#### 2. **Sales This Year vs Last Year by Category**
- Technology remains strong (~45K)
- Furniture and Office Supplies declined (both at 26K in 2023)

#### 3. **YoY % Change in Profit**
- Highest growth in 2021 (+31.20%)
- Sharp decline in 2023 (-27.15%)

#### 4. **YoY % Change in Orders**
- Orders fell from 29 (2021) to 19 (2023), a -17.39% drop

### 🧮 Filters & Slicers Used:
- **Country Slicer**: Filter performance by country
- **Year Context**: Present across visuals for multi-year trend analysis
- All visuals interact dynamically with the selected filters

---

## 👩‍💼 Employee Performance Dashboard

**Purpose**: Rank employees based on sales and profit

**Visuals Used**:
- **Horizontal Bar Chart**: Top Sellers by Total Sales
- **Horizontal Bar Chart**: Total Profit by Employee Name

**Filters/Slicers**:
- Year (Radio buttons: 2020, 2021, 2022, 2023)

![image alt](https://github.com/Bhavani1989/TataNeuSkillDashboard/blob/d45df698fe374cee51cd3f96c8ec1d360b4d97a6/Employee_performane.png)

This tab showcases **individual contributions** to sales and profit, enabling recognition of top performers.

### 🔝 Top Sellers by Total Sales
- **Brittney Pearson**: 18.2K  
- **Brady Powers**: 12.7K  
- **Johnathan Riley**: 9.9K  
- **Christine Gallegos**: 8.7K  
- **Sara Mitchell**: 7.3K  

### 💰 Top Employees by Total Profit
- **Kaitlyn Moore**: 611  
- **Stephanie Wheeler**: 480  
- **Paula Miller**: 445  
- **Julian Brown**: 435  
- **Amanda Evans**: 430  

### 🧮 Filters & Slicers Used:
- **Year Slicer**: Radio button list to view performance in a selected year (2020–2023)
- All visuals update instantly based on selected year
- Employee names shown dynamically based on filtered data

---

## 📦 Product Information Dashboard

**Purpose**: Identify best and worst-performing products

**Visuals Used**:
- **Scatter Plot**: Total Sales vs. Total Profit by Product

**Filters/Slicers**:
- Year (Radio buttons)
- Region (Dropdown)
- Product Category (optional)


This section gives a **product-level profitability and sales snapshot**.

### 🔍 Chart: Total Sales vs. Total Profit (Bubble Plot)
- Each dot represents a product.
- **Desk** stands out as the highest performer with:
  - ~18K in Total Sales
  - ~1100 in Total Profit
- Other notable performers:
  - **Digital Camera**, **Sticky Notes**, **Printer Paper**
- Low/no-profit items:
  - **Side Table**, **Keyboard**, **Cabinet**

### 🧮 Filters & Slicers Used:
- **Year Slicer**: Year-based filter (2020–2023) to observe trends over time
- **Region Slicer**: Select region-wise performance (e.g., Europe, Asia, etc.)
- **Product Name Filters**: Included behind the scenes for dynamic visual interactivity

---

## 🧩 Data Assumptions

- Simulated and anonymized sales and profit data from **2020 to 2023**
- Monthly granularity with segmentation by **category**, **subcategory**, **region**, and **customer segment**
- Internal identifiers and structures mimic real-world business systems

---

## 💡 Technologies Used

- **Microsoft Power BI** — Data modeling, visualization, and interactivity
- **DAX** — For calculated measures and KPIs
- **Excel/CSV files** — As structured data sources

---
