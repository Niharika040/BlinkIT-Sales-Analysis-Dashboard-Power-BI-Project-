
# BlinkIT Sales Analysis Dashboard (Power BI Project)

This project provides an in-depth **sales analysis for BlinkIT (India’s last-minute grocery delivery app)** using **Power BI**.  
The dashboard highlights **key performance metrics**, uncovers **sales patterns**, and provides **actionable insights** for business decisions.

---

## Project Objective
The main objective of this project is to analyze **BlinkIT’s grocery sales data** to answer the following business questions:
- Which **outlet type** performs best in terms of sales?
- Which **product categories (Item Types)** contribute most to revenue?
- How does **outlet location (Tier 1/2/3)** impact sales?
- Does **outlet size** (Small/Medium/High) influence performance?
- Which **fat content** products (Low Fat vs Regular) are more profitable?
- How are **sales trends changing over years** (based on establishment year)?
- What are the **customer ratings trends** across items and outlets?

---

## Dataset Information
- **File:** `BlinkIT Grocery Data.xlsx` [BlinkIT Grocery Data](./BlinkIT Grocery Data.xlsx) 
- **Rows:** 8,523  
- **Columns:** 12  

###  Key Columns
| Column Name                 | Description |
|------------------------------|-------------|
| Item Identifier              | Unique product code |
| Item Type                    | Category (Fruits, Snacks, Dairy, etc.) |
| Item Fat Content             | Fat category (Regular, Low Fat) |
| Item Weight                  | Product weight |
| Item Visibility              | % visibility inside store |
| Sales                        | Sales value ($) |
| Rating                       | Customer rating (1-5) |
| Outlet Identifier            | Unique outlet code |
| Outlet Size                  | Small / Medium / High |
| Outlet Location Type         | Tier 1 / Tier 2 / Tier 3 |
| Outlet Type                  | Supermarket Type1, Type2, Type3, Grocery Store |
| Outlet Establishment Year    | Year outlet started |

---

## Data Cleaning & Preparation
Before building the dashboard, the dataset was cleaned in Power BI:
- Replaced inconsistent values in **Item Fat Content** (`LF`, `low fat`, `Low Fat` → `Low Fat`).   
- Added calculated columns:
  - **Total Sales**
  - **Average Sales per Item**
  - **Sales Contribution % per Category**
---

## Dashboard Features
The Power BI dashboard is **interactive** with multiple slicers and KPIs:

### KPIs
- **Total Sales:** `$1.20M`
- **Average Sales per Item:** `$141`
- **Average Rating:** `3.9 ⭐`
- **No. of Items:** `8,523`

### Charts & Visuals
1. **Sales by Item Type** → Bar chart (Top categories: Fruits, Snacks, Household).  
2. **Sales by Fat Content** → Donut chart (Regular vs Low Fat).  
3. **Sales by Outlet Type** → Matrix with KPIs for each type.  
4. **Outlet Establishment Trend** → Line chart showing sales by year.  
5. **Outlet Size Performance** → Donut chart (Medium outlets dominate).  
6. **Outlet Location Contribution** → Bar chart (Tier 3 has highest sales).  
7. **Fat Content by Outlet** → Clustered bar chart.  

---

## Key Insights & Business Impact

###  Outlet Performance
- **Supermarket Type1 generates 65% of sales ($788K).**  
   *Expand Type1 model across more locations.*  
- **Tier 3 outlets lead with $472K sales.**  
   *Focus growth strategy on semi-urban/rural regions.*  
- **Medium outlets outperform ($508K).**  
   *Scale medium-sized stores vs. small outlets.*  

### Product Insights
- **Regular fat products drive nearly 2x sales vs Low Fat.**  
   *Boost promotions for Regular fat, but invest in health-conscious SKUs.*  
- **Fruits & Snacks dominate ($360K).**  
   *Bundle with weak categories like Breakfast/Seafood for cross-sell.*  
- **Breakfast & Seafood <2% of sales.**  
   *Improve marketing or phase out underperformers.*  

### Customer Insights
- **Avg Rating: 3.9/5** → *room for quality improvement.*  
- **High visibility ≠ high sales** → *optimize store displays & targeted promos.*  

### Time Trends
- **Peak sales in 2018–2020 ($205K in 2018).**  
   *Leverage heavy promos in early years of new outlets.*  
- **Decline post-2020.**  
   *Explore new product lines & competitive pricing.*  

---
