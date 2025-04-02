# 🍕Pizza Sales Analysis
## 📌Project Overview
This project aims to analyze pizza sales data using SQL for data extraction and transformation and Power BI for interactive visualizations. The dashboard provides insights into total revenue, best-selling and worst-selling pizzas, sales trends, and customer preferences.

## 📊Dataset Used
- <a href="https://github.com/KomalThakur204/Pizza_Sales_Analysis/blob/main/pizza_sales_excel_file%20(1).xlsx">Dataset</a>

## 📊 Key Features
- ✅ **Total Sales & Revenue Analysis** – Displays key metrics like total revenue, total orders, and average order value.
- ✅ **Daily & Monthly Sales Trends** – Identifies peak sales days and seasonal variations.
- ✅ **Top-Selling & Least-Selling Pizzas** – Highlights the most and least popular pizza types based on revenue, quantity, and total orders.
- ✅ **Category & Size Analysis** – Breaks down sales by pizza category and size to understand customer preferences.
- ✅ **Best/Worst Sellers Dashboard** – Identifies the best-performing and underperforming pizzas.

## 🛠️Tools & Technologies Used
- **SQL (MySQL)** – For data extraction, transformation, and querying.
- **Power BI** – For interactive data visualization and dashboard creation.
- **Excel** – As a data source.

## 📊 KPI Requirements  

The following Key Performance Indicators (KPIs) were used to analyze pizza sales performance:  

- **Total Revenue** 💰 – The total earnings from pizza sales.  
- **Total Pizzas Sold** 🍕 – The total number of pizzas sold during the selected period.  
- **Total Orders** 📦 – The total number of orders placed.  
- **Average Order Value (AOV)** 📈 – The average revenue per order.  
- **Average Pizzas Per Order** 🛒 – The average number of pizzas in each order.  

---

## 📊 Chart Requirements  

The project includes multiple visualizations to represent sales performance:  

### **Sales Trends**  
- **Daily Trend for Total Orders** 📅 – Bar chart showing daily order trends.  
- **Monthly Trend for Total Orders** 📆 – Line chart tracking total orders per month.  

### **Category and Size Analysis**  
- **% of Sales by Pizza Category** 🍕 – Donut chart showing the contribution of different pizza categories to total sales.  
- **% of Sales by Pizza Size** 📏 – Donut chart analyzing the distribution of pizza sizes sold.  
- **Total Pizza Sold by Category** 📊 – Horizontal bar chart comparing total sales across pizza categories.  

### **Best & Worst Sellers**  
- **Top 5 Pizzas by Revenue** 💵 – Bar chart of the highest revenue-generating pizzas.  
- **Top 5 Pizzas by Quantity** 🔢 – Bar chart of the most frequently sold pizzas.  
- **Top 5 Pizzas by Total Orders** 🏆 – Bar chart showing pizzas with the most orders.  
- **Bottom 5 Pizzas by Revenue, Quantity, and Orders** 📉 – Identifying the least popular pizzas.  

These KPIs and charts provide insights into sales performance, customer preferences, and business trends. 🚀  

## 🔄 Process Workflow  

### **1️⃣ Data Cleaning in Excel** 📑  
Before performing analysis, the dataset was cleaned and preprocessed in Excel.  
**Key Steps:**  
✔️ Removed duplicate records and missing values.  
✔️ Standardized date formats and column names.  
✔️ Ensured data consistency for categories and sizes. 

### **2️⃣ Data Exploration & Transformation in SQL** 🛠️  
The cleaned data was imported into SQL for exploration and transformation.  
**Key SQL Tasks:**  
✔️ Extracted relevant columns for analysis.  
✔️ Aggregated sales data (total revenue, orders, etc.).  
✔️ Identified top and bottom-performing pizzas.  
✔️ Created calculated fields for KPIs like Average Order Value. 

 📄 **[SQL Queries File](https://github.com/KomalThakur204/Pizza_Sales_Analysis/blob/main/PIZZA%20SALES%20SQL%20QUERIES.pdf)**  
### **3️⃣ Data Visualization in Power BI** 📊  
The transformed data was visualized using Power BI to gain meaningful insights.  
**Key Visualizations:**  
✔️ **Sales Trends:** Daily & Monthly Sales Overview.  
✔️ **Category Analysis:** Sales by pizza size and type.  
✔️ **Top & Bottom Performers:** Best & worst-selling pizzas.  
✔️ **KPI Dashboard:** Total Revenue, Orders, and Average Order Value.  

 📊 **[Power BI Dashboard File](https://github.com/KomalThakur204/Pizza_Sales_Analysis/blob/main/Pizza_Sales.pbix)**  
📸 **Dashboard Screenshots**![Home Dashboard](https://github.com/user-attachments/assets/d4d193bb-6bbb-48e1-a627-bcd7ac06cf75)
![BestWorstSeller](https://github.com/user-attachments/assets/cfce927d-69e6-40b4-934b-eeacbc562961) 

---

This structured process ensures a clear data pipeline from **cleaning ➝ analysis ➝ insights** 🚀.  
## 📈 Key Insights  

📌 **Highest sales** occur on weekends, especially **Friday and Saturday evenings**.  
📌 **July and January** have the most orders, indicating **peak months** for sales.  
📌 **Classic pizzas** contribute the most to overall revenue.  
📌 **Large-sized pizzas** generate the **highest revenue** among all sizes.  
📌 Some pizzas have **significantly low sales**, indicating a need for **menu optimization**.  

These insights help in understanding customer preferences and optimizing sales strategies.  
## 📜 How to Use This Repository
- 1️⃣ Clone the repository:
-- git clone https://github.com/KomalThakur204/Pizza_Sales_Analysis
- 2️⃣ Import the dataset into your SQL database.
- 3️⃣ Run the SQL queries to analyze the data.
- 4️⃣ Open the Power BI file (.pbix) to explore the interactive dashboards.
