# Superstore Sales & Profitability Analysis

## Project Overview

**Superstore Sales & Profitability Analysis** is a Power BI project focused on understanding the overall performance and profitability of a retail business using the Superstore dataset.

The analysis examines sales, profit and profitability across different categories, subcategories, products, customers and regions. It also investigates potential factors associated with weaker profitability, including discount levels and product performance.

The project follows a complete data analytics workflow, from data cleaning and transformation through to data modelling, DAX measure creation, visual analysis and interactive dashboard design. The final dashboard is designed to help management identify areas of strong and weak performance and determine where further investigation may be required.

## Business Problem

The project aims to identify areas where the business is underperforming and investigate potential factors associated with lower profitability.

The analysis focuses on questions such as:

* Is profit keeping pace with sales growth?
* Which categories and subcategories are contributing most to profitability?
* Which products and customers generate the most value?
* Where are profitability problems concentrated?
* Is there an association between discount levels and profitability?
* Is operational performance improving over time?

## Tools & Technologies

* **Power BI Desktop** — dashboard development, data modelling and visualisation
* **Power Query** — data cleaning and transformation
* **DAX** — calculated measures and business analysis
* **GitHub** — project documentation and portfolio presentation

## Data Preparation & Modelling

The Superstore dataset was prepared in Power Query before being loaded into the Power BI data model. Data transformations included creating a **Shipping Days** field to measure the time between order and shipment, as well as a **Discount Band** classification to group transactions according to discount levels.

A dimensional data model was created to separate the main transaction data from supporting dimensions. The model includes a central **Sample-Superstore** fact table connected to **Date, Product and Customer** dimensions.

DAX measures were then created to calculate key business metrics including total sales, total profit, profit margin, year-over-year sales growth, product rankings and other profitability measures used throughout the analysis.

## Analysis Performed

The dashboard was developed around several business-focused areas of analysis:

### Sales & Profitability

* Analysed sales and profit trends from 2014 to 2017.
* Compared sales growth with changes in total profit and profit margin.
* Examined profitability across product categories and subcategories.

### Product Performance

* Identified top-performing products by sales and profit.
* Analysed loss-making products and subcategories.
* Investigated product-level profitability using sales, profit margin and discount measures.

### Customer Analysis

* Compared sales and profitability across customer segments.
* Identified high-value customers and examined the products contributing to their sales.

### Discount & Profitability Analysis

* Analysed the relationship between discount levels and profitability.
* Investigated areas where higher discount levels were associated with weaker profit margins.
* Examined Furniture and its subcategories in greater detail, particularly Tables.

### Regional & Operational Analysis

* Compared profitability across regions and investigated areas with weaker margins.
* Analysed shipping performance over time to determine whether delivery times were improving.

## Key Findings

* **Sales grew consistently from 2014 to 2017**, while total profit also increased each year. However, profit did not keep pace with sales growth, resulting in a profit margin that did not consistently improve.
* **Furniture had the lowest profit margin** among the three product categories, despite generating substantial sales.
* **Tables were the main source of Furniture losses**, making the subcategory a key area for further investigation.
* **Higher discount levels were associated with weaker profitability in several areas**, particularly within Furniture and Tables. This relationship was investigated further at subcategory and product level.
* **The Central region had the lowest profit margin** among the four regions, indicating an area requiring further investigation.
* **Shipping performance gradually improved**, with average shipping time declining from approximately 4.00 days in 2014 to 3.91 days in 2017.

## Recommendations

Based on the analysis, the following areas should be considered for further investigation:

* **Review pricing and discount strategies**, particularly in areas where higher discounts are associated with weaker profitability.
* **Investigate Furniture, especially Tables**, to understand the product-level factors contributing to losses.
* **Examine the Central region in greater detail** by breaking down its performance by state, category, subcategory and product.
* **Focus on improving profit margins while protecting sales**, rather than pursuing sales growth without considering profitability.
* **Maintain awareness of operational performance**, as average shipping times showed gradual improvement over the period analysed.

## Dashboard Preview

The Power BI report consists of five analytical pages:

1. **Executive Overview** — Provides a high-level view of sales growth, profitability, regional performance and operational performance.
2. **Product & Customer Analysis** — Examines performance across categories, subcategories and customer segments.
3. **Product Profitability** — Investigates product and subcategory profitability, including discount levels and loss-making products.
4. **Customer & Product Rankings** — Identifies high-value customers and the products contributing to their sales.
5. **Product Performance** — Provides a detailed view of product sales, profit, profitability and rankings.


### Dashboard Screenshots

#### Executive Overview

![Executive Overview](Executive%20Overview.png)

#### Product & Customer Analysis

![Product & Customer Analysis](Product%20%26%20Customer%20Analysis.png)

#### Product Profitability

![Product Profitability](Product%20Profitability.png)

#### Customer & Product Rankings

![Customer & Product Rankings](Customer%20%26%20Product%20Rankings.png)

#### Product Performance

![Product Performance](Product%20Performance.png)

## Project Structure

```text
superstore-sales-profitability-analysis/
│
├── README.md
├── Sample-Superstore.csv
├── Superstore Sales & Profitability Analysis.pbix
├── Executive Overview.png
├── Product & Customer Analysis.png
├── Product Profitability.png
├── Customer & Product Rankings.png
├── Product Performance.png
│
└── Data/
    └── .gitkeep
```

The repository contains the Power BI report, source dataset, dashboard screenshots and project documentation supporting the analysis.

```




