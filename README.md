# ☕ Coffee Sales Dashboard

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Pivot Table](https://img.shields.io/badge/Skill-Pivot_Table-blue?style=flat-square&logo=microsoft-excel)
![Formula](https://img.shields.io/badge/Skill-Formulas-yellow?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

![EXCEL_X4RJXVSVqs](https://github.com/user-attachments/assets/6c62ac23-a2ef-4f31-9bd6-c6dc2d241158)

## 🧭 Overview
This dashboard was created to help business managers and sales analysts monitor coffee sales performance from 2019 to 2022. By leveraging an interactive interface, users can quickly identify sales trends, top-performing products, and key geographic markets.

It provides insights on:
- Total sales, profit, orders, and quantity sold.
- Top countries and cities by sales performance.
- Annual and monthly sales trends.
- Product and roast type sales distribution.
- Customer loyalty and product size impact on sales.

▶️ [Coffee_Sales_Dashboard](./coffeeOrdersData.xlsx) — This is the main file containing the interactive dashboard.

## 🗂️ Dataset Description

The dataset contains coffee sales transaction data from 2019–2022, including:

- **📅 `Year`** — The sales year.
- **🌍 `Country`** — The country of sale (e.g., Ireland, United Kingdom, United States).
- **☕ `Coffee Type`** — The type of coffee product (e.g., Arabica, Excelsa, Liberica, Robusta).
- **🔥 `Roast Type`** — The coffee's roast level (Light, Medium, Dark).
- **🛍 `Product Size`** — The size of the product package (e.g., 0.2 Kg, 0.5 Kg).
- **💰 `Sales`** — Total sales amount.
- **💵 `Profit`** — Net profit from sales.
- **🛒 `Orders`** — The number of orders.

## 🛠️ Excel Skills Used

This dashboard primarily utilizes the following Excel features:

- **📊 PivotTables**: For summarizing and analyzing sales data efficiently.
- **⚙️ Slicers**: To provide interactive filtering by `Country`, `Coffee Type`, and `Year`.
- **🧮 Formulas**: Key lookup and reference formulas such as `XLOOKUP`, `INDEX`, and `MATCH` to dynamically retrieve and manipulate data.

These tools allow for dynamic, user-friendly data exploration without the need for advanced Power Query or DAX.

## 📊 Dashboard Build Details

### 🔹 Annual Sales Profit Overview

<img width="531" height="307" alt="EXCEL_BOHpH69Dz8" src="https://github.com/user-attachments/assets/8f2f48d4-89f9-4a09-8e6f-00dd249b8e75" />

- ⚙️ **Implementation**: A combo chart showing `Total Sales` as a bar chart and `Total Profit` as a line chart.
- 🖼️ **Visualization Style**: Displays performance from 2019 to 2022, with a secondary axis for profit to better highlight trends.
- 🧭 **Key Insight**: The chart reveals a consistent increase in sales and profit, with **2022 (data available until August) being the peak year** for both metrics.

### 🔹Monthly Sales Performance

<img width="531" height="307" alt="image" src="https://github.com/user-attachments/assets/925dd78c-b4a6-4ee1-93e0-3126361f693e" />

- ⚙️ **Implementation**: A stacked bar chart showing monthly total sales, broken down by coffee type.
- 🖼️ **Visualization Style**: Each bar represents one month's total sales, with colored segments showing the sales contribution from each coffee type (Robusta, Liberica, Excelsa, Arabica).
- 🧭 **Key Insight**: Sales tend to peak in **March** and **June**, while **August** shows the lowest sales. This indicates a seasonal pattern in sales. Further analysis is needed to understand the reasons behind these peaks and dips.

### 🔹Sales by Country

<img width="316" height="296" alt="image" src="https://github.com/user-attachments/assets/c3fcbbbe-ece7-4778-8f07-1feb8f547ea6" />

- ⚙️ **Implementation**: A KPI card and bulleted list displaying total sales per country.
- 🖼️ **Visualization** Style: Highlights the total sales for each country in bold text, with a prominent percentage for the largest contributor.
- 🧭 **Key Insight**: The United States consistently leads in sales each year with a total of $35,639, accounting for 79% of total sales, far outpacing Ireland and the United Kingdom.

### 🔹Top 10 Cities by Sales

<img width="316" height="438" alt="image" src="https://github.com/user-attachments/assets/e9286b73-bcba-494d-b373-6447e97353b5" />

- ⚙️ **Implementation**: A bar chart displaying the top 10 cities based on Total Sales.
- 🖼️ **Visualization** Style: Horizontal bars for easy comparison, ranked from highest to lowest sales.
- 🧭 **Key Insight**: Washington leads with $1,067 in sales, followed by Houston and Toledo, indicating these are key urban markets for the business.


### 🔹Product Sales Breakdown

<img width="443" height="303" alt="image" src="https://github.com/user-attachments/assets/3f14f178-71e2-4208-97d2-aa2f9e176abf" />

- ⚙️ **Implementation**: A horizontal bar chart showing total sales for each coffee type.
- 🖼️ **Visualization Style**: Bars are sorted from highest to lowest sales, with clear value labels next to each bar for easy comparison.
- 🧭 **Key Insight**: **Excelsa** is the best-selling product with total sales of **$12,306**, followed by Liberica and Arabica. **Robusta** has the lowest sales (**$9,005**), indicating a clear market preference for certain coffee types.

### 🔹Sales by Roasted Type

<img width="320" height="304" alt="image" src="https://github.com/user-attachments/assets/02d64ac1-8c84-43a9-a80a-87354c063961" />

- ⚙️ **Implementation**: A standard pie chart.
- 🖼️ **Visualization Style**: Slices represent the percentage of total sales for each Roast Type.
- 🧭 **Key Insight**: Light Roast coffee accounts for the largest share of sales (38%), indicating it is the most popular roast level among customers.

### 🔹Product Size Sales

<img width="378" height="302" alt="image" src="https://github.com/user-attachments/assets/3a32fdce-a2e2-4c8c-9a32-7df7d4e01092" />

- ⚙️ **Implementation**: Text boxes displaying total sales for each product size.
- 🖼️ **Visualization Style**: Coffee package icons represent each size (0.2 Kg, 0.5 Kg, 1.0 Kg, 2.5 Kg), with sales values shown below. Icon sizes reflect the product sizes visually.
- 🧭 **Key Insight**: The largest size (**2.5 Kg**) is the most popular, with total sales of **$23,786**, indicating customer preference for bulk purchases, possibly due to loyalty or frequent use.


### 🔹Loyalty Segment Sales

<img width="378" height="306" alt="image" src="https://github.com/user-attachments/assets/ce1160ea-3976-4048-a0f3-372471eaef30" />

- ⚙️ **Implementation**: A donut chart.
- 🖼️ **Visualization** Style: One slice for "Yes" (loyal customers) and one for "No" (non-loyal customers).
- 🧭 **Key Insight**: 54% of sales come from non-loyal customers. This highlights a significant opportunity for the business to focus on customer retention strategies and loyalty programs to convert these customers.

## ✅ Conclusion
This dashboard transforms raw sales data into actionable business intelligence through a blend of clean design, intuitive filters, and powerful analytics. It demonstrates the ability to turn data into a structured, insight-driven tool—blending logical implementation with user-friendly design to drive effective decision-making

## 💬 Feedback & Suggestions

I’m always open to feedback!  
If you have suggestions to improve this dashboard or want to share ideas, feel free to reach out or open an issue in this repository.


