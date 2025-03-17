# ☕ Coffee Business Data Analysis

Running a coffee business sounds exciting, but making smart business decisions requires more than just great coffee. With thousands of transactions happening across different countries, we needed to break down the data and find answers to some key questions:

- **Who are our most valuable customers?** 👤  
- **Which country contributes the highest sales?** 🌍  
- **What coffee type generates the most revenue?** ☕  
- **Which products bring the highest profit?** 💰  
- **How do sales change over time?** 📊  

Using **Excel functions, data cleaning techniques, and an interactive dashboard**, we transformed raw data into meaningful insights. Let's explore! 🔍

---

## 📂 Understanding the Data

Our dataset consists of **three key tables**, each providing a different piece of the puzzle:

### 1️⃣ Orders Data 📦
This table tracks every coffee sale made, capturing essential transaction details:
- **Order ID** – Unique identifier for each purchase.
- **Order Date** – The date when the order was placed.
- **Customer ID** – Links to the customer who placed the order.
- **Product ID** – Identifies the type of coffee sold.
- **Quantity** – The number of coffee units bought.
- **Sales Amount** – Total revenue from the sale.
- **Country** – The country where the order was placed.
- **Coffee Type & Roast Type** – Specific details about the coffee purchased.
- **Loyalty Program** – Indicates if the customer is part of the loyalty scheme.

### 2️⃣ Customers Data 👥
This table gives us insight into who is buying the coffee:
- **Customer Name** – Identifies the buyer.
- **Email & Phone Number** – Contact details.
- **Address & Country** – Location insights.
- **Loyalty Program Membership** – Helps track repeat customers.

### 3️⃣ Products Data ☕
This table focuses on coffee varieties and their pricing:
- **Product ID** – Unique identifier for each coffee type.
- **Coffee Type** – Arabica, Robusta, Excelsa, Liberica.
- **Roast Type** – Light, Medium, or Dark roast.
- **Size** – The weight of the coffee pack.
- **Unit Price** – The selling price per unit.
- **Profit Margin** – The amount of profit per sale.

---

## 🛠 Data Processing in Excel – Cleaning & Transformation

Before diving into analysis, we had to clean and structure the data. Here's what we did:

- **🔹 Merging Data:** Since the orders table contained only Customer IDs and Product IDs, we used **XLOOKUP and INDEX MATCH** to pull in the actual customer names and coffee details.
- **🔹 Handling Duplicates & Missing Values:** Removed redundant records and filled missing fields to ensure data accuracy.
- **🔹 Creating New Metrics:** Calculated total sales per order, revenue per customer, and profit margins to enhance the analysis.

---

## 📈 Key Insights from the Data

### 1️⃣ Who are our most valuable customers? 👤
📌 _Insert Screenshot of Top 5 Customers Table_

- The **top 5 customers contribute 15% of total revenue**.
- Customers in the **loyalty program** tend to spend more than regular buyers.
- High spenders mostly purchase **larger coffee sizes (2.5kg packs).**

### 2️⃣ Which country generates the highest sales? 🌍
📌 _Insert Screenshot of Country Sales Chart_

- **United States** leads the market with **$35,638** in total sales, followed by **Ireland ($6,696) and the UK ($2,798).**
- **Robusta** is the favorite in Ireland, while **Arabica dominates the US market.**
- Certain regions show a **higher demand for medium roast coffee**, indicating consumer preference differences.

### 3️⃣ Bestselling Coffee Type & Profitability ☕
📌 _Insert Screenshot of Sales by Coffee Type Chart_

- **Light Roast (Arabica)** is the **top-seller AND the most profitable**.
- **Medium roast** varieties sell well but with lower margins, indicating a balance between popularity and profitability.
- Larger coffee packs (**2.5kg**) contribute more to total sales, making them a strategic product for revenue growth.

### 4️⃣ Sales Performance Over Time 📊
📌 _Insert Screenshot of Sales Trends Chart_

- **Sales peak in October - December**, likely due to holiday demand.
- **Over the years, sales increased by 18% between 2019-2021**, showing a steady business growth.
- **Seasonal trends** suggest potential for **seasonal promotions to maximize profits**.

---

## 📊 Final Dashboard – Everything in One Place

📌 _Insert Screenshot of Full Excel Dashboard_

After processing and analyzing the data, we created an **interactive Excel dashboard** that provides a complete business overview:

✅ **Top Customers** – Identifies the most valuable buyers.  
✅ **Sales by Country** – Breaks down revenue sources by region.  
✅ **Coffee Type Performance** – Highlights bestsellers and profit margins.  
✅ **Monthly Sales Trends** – Visualizes fluctuations over time.  

---

## 📂 Files Included in This Project

📁 **Final_Dashboard.xlsx** – The interactive Excel Dashboard.  
📁 **coffeeOrders_Data.xlsx** – The raw data used for analysis.  
📁 **queries/** – The Excel formulas and processed tables.  
📁 **visualizations/** – Screenshots of key charts and dashboards.  

---

## 🔧 How to Use This Dashboard

1️⃣ Download **Final_Dashboard.xlsx** and open in Excel.  
2️⃣ Use the **filter options** to adjust the data view.  
3️⃣ Explore different sections to understand **sales trends, customer behavior, and profitability.**  

---

## 🚀 Future Enhancements & Next Steps

📌 **Automate real-time tracking** using **Power BI**.  
📌 **Develop forecasting models** to predict seasonal demand.  
📌 **Analyze customer retention trends** to improve loyalty programs.  

--- 

🌟 If you found this project useful, consider **starring** ⭐ the repository on GitHub!
