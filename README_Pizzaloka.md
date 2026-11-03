# Pizzaloka Sales Analysis

## Project Overview

Pizzaloka is a pizza restaurant sales analysis project focused on understanding sales performance, customer ordering patterns, and product performance. The analysis uses one year of transaction-level sales data, from **January 1 to December 31, 2015**.

The goal is to turn raw sales records into useful business information that can help the restaurant understand what sells, when customers place orders, and where it can focus its sales and marketing efforts.

## Business Problem

A restaurant needs more than total revenue to understand how well its business is performing. Without a clear view of sales patterns, management may find it difficult to:

- Identify the pizzas and categories that contribute most to revenue.
- Understand which pizza sizes customers purchase most often.
- Recognize the busiest days and hours.
- Identify products with relatively low sales.
- Make informed decisions about promotions, menu planning, and staffing.

Pizzaloka's sales data provides an opportunity to answer these questions and support better day-to-day and strategic business decisions.

## Project Objectives

This analysis aims to:

1. Measure overall sales performance using revenue, order volume, and quantity sold.
2. Evaluate sales performance across pizza names, categories, and sizes.
3. Identify daily and hourly ordering trends.
4. Compare high-performing and low-performing products.
5. Translate the findings into practical recommendations for the business.

## Dataset

The workbook contains **48,620 sales records** covering the 2015 calendar year and includes fields such as:

- `order_id` – identifier for each customer order.
- `pizza_id` – identifier for each pizza record.
- `pizza_name` and `pizza_name_id` – pizza product details.
- `quantity` – number of pizzas sold on a sales record.
- `order_date`, `order_day`, `order_time`, and `order_hour` – order timing information.
- `unit_price` and `total_price` – pricing and sales value.
- `pizza_size` and `pizza_category` – product size and category.
- `pizza_ingredients` – ingredients used in each pizza.

The dataset contains **32 distinct pizza products** across **4 categories**: Classic, Supreme, Chicken, and Veggie.

## Tools Used

- **Microsoft SQL Server** – querying and analysing the sales data, including aggregations and comparisons across products, dates, and order times.
- **Microsoft Excel** – reviewing and summarising results, building PivotTables and charts, and presenting the findings in a sales dashboard.

## Analysis Performed

### 1. Overall Sales Performance
Calculated key performance indicators to establish the restaurant's overall performance:

- Total revenue
- Total orders
- Total pizzas sold
- Average order value
- Average pizzas per order

### 2. Product Performance
Compared sales by pizza name to identify the best-selling and lowest-selling products by quantity, as well as the products generating the highest and lowest revenue.

### 3. Category Performance
Examined the contribution of the four pizza categories to total revenue to understand which menu categories generated the largest share of sales.

### 4. Pizza Size Performance
Compared revenue and quantity sold across pizza sizes to identify the sizes that contributed most to sales.

### 5. Daily and Hourly Trends
Analysed order activity by day of the week and hour of the day to identify busy periods and understand when demand was highest.

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Revenue | 817,860.05 |
| Total Orders | 21,350 |
| Total Pizzas Sold | 49,574 |
| Average Order Value | 38.31 |
| Average Pizzas per Order | 2.32 |

*Note: The source workbook does not specify a currency symbol, so revenue and order value are shown without a currency label.*

## Key Insights

### 1. Strong Overall Sales Activity
Pizzaloka generated **817,860.05 in revenue** from **21,350 orders**, selling **49,574 pizzas** during the year. Customers purchased an average of approximately **2.32 pizzas per order**, with an average order value of **38.31**.

### 2. Classic Was the Leading Revenue Category
The **Classic** category generated approximately **26.91% of total revenue**, making it the largest revenue contributor among the four categories. Supreme followed at approximately **25.46%**, while Chicken and Veggie contributed approximately **23.96%** and **23.68%**, respectively. Revenue was relatively balanced across categories.

### 3. Large Pizzas Generated the Highest Revenue
Large pizzas contributed approximately **45.89% of total revenue**, the highest share among all sizes. Medium pizzas contributed approximately **30.49%**, while Regular pizzas contributed approximately **21.77%**. XL and XXL sizes together represented a much smaller share of revenue.

### 4. Friday Was the Busiest Day
Friday recorded the highest order count, with **3,538 orders**. Thursday followed with **3,239 orders**, while Sunday had the lowest order count at **2,624**. This suggests that demand was strongest toward the end of the working week.

### 5. Lunch and Evening Were the Busiest Periods
The busiest hour was **12:00 PM**, with **2,520 orders**, followed by **1:00 PM** with **2,455 orders**. Order activity also increased during the early evening, particularly between **5:00 PM and 7:00 PM**. These periods are important when planning staff coverage and food preparation.

### 6. Best-Selling Pizzas by Quantity
The **Classic Deluxe Pizza** was the top-selling product by quantity, with **2,453 pizzas sold**. It was followed by the Barbecue Chicken Pizza (2,432), Hawaiian Pizza (2,422), Pepperoni Pizza (2,418), and Thai Chicken Pizza (2,371).

### 7. Lowest-Selling Pizza by Quantity
The **Brie Carre Pizza** had the lowest sales quantity, with **490 pizzas sold**. This may be an opportunity to review its pricing, promotion, customer appeal, or menu positioning before making any decision about whether to retain it.

### 8. Highest Revenue-Generating Pizza
The **Thai Chicken Pizza** generated the highest revenue, approximately **43,434.25**, followed by the Barbecue Chicken Pizza at **42,768.00** and the California Chicken Pizza at **41,409.50**. This shows that the products generating the most revenue are not necessarily identical to the products ranked highest by quantity sold.

## Business Recommendations

Based on the findings, Pizzaloka's management could consider the following actions:

1. **Prioritise popular products:** Maintain sufficient ingredients and preparation capacity for the Classic Deluxe, Barbecue Chicken, Hawaiian, Pepperoni, and Thai Chicken pizzas.
2. **Use large pizzas in sales campaigns:** Since Large pizzas account for the largest share of revenue, test bundles or meal deals that encourage customers to purchase this size.
3. **Plan staffing around peak periods:** Ensure adequate kitchen and service coverage around lunchtime and early evening, with particular attention to Fridays.
4. **Review low-selling products:** Investigate customer feedback, ingredient costs, pricing, and promotion for the Brie Carre Pizza before deciding whether to adjust or remove it.
5. **Build on category balance:** Since revenue is distributed fairly evenly across the four categories, use targeted promotions to maintain interest across the menu rather than relying on a single category.
6. **Increase order value carefully:** Test add-ons, sides, drinks, or multi-pizza bundles to encourage customers to add items to their orders, then monitor whether these offers improve average order value.

## Conclusion

The analysis provides Pizzaloka with a clearer picture of its sales performance across products, categories, sizes, days, and hours. It highlights the products and periods that contribute most to sales and identifies areas where management can investigate opportunities for improvement.

By using these findings to guide inventory planning, staffing, promotions, and menu decisions, Pizzaloka can make more informed, data-driven business decisions.

## Repository Contents

```text
Pizzaloka-Sales-Analysis/
├── Pizzaloka Sales File.xlsx
├── README.md
└── Sales Performance Dashboards/
    └── dashboard-preview.png
```
