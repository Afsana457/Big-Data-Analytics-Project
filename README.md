# Big-Data-Analytics & Visualization-Project
End-to-end Big Data Analytics &amp; Visualization Project (Python + Tableau + Power BI)

📌 **Course:**  Big Data Analytics and Data Visualization  
📌 **Faculty:** Ahmed Imran Kabir, Assistant Professor, School of Business & Economics, United International University (UIU)  

This project demonstrates **end-to-end analytics skills**:  
- Cleaning and transforming raw transaction data in **Python**  
- Designing interactive dashboards in **Tableau**  
- Building executive-level reports in **Power BI**  

---

## 🔹 Part A: Data Cleaning (Python)  
Performed comprehensive preprocessing to ensure clean, consistent data:  
1. Removed duplicate TransactionIDs.  
2. Handled missing values in CustomerID, ProductID, and PaymentMethod.  
3. Standardized categories: Gender, Country, PaymentMethod.  
4. Fixed outliers in Age, Quantity, and UnitPrice.  
5. Converted Discount into numeric percentages (0–100).  
6. Recalculated TotalAmount = Quantity × UnitPrice × (1 – Discount).  
7. Standardized PurchaseDate (YYYY-MM-DD) and extracted Year, Month, Weekday.  
 
👉 [View Data Cleaning Notebook] https://drive.google.com/file/d/1ZAE4nekZT8-LQO8hWMpIzoHwlsC8I1oy/view?usp=sharing
---

## 🔹 Part B: Tableau Dashboards  
Built interactive dashboards to explore key insights:  

- **Sales Dashboard**  
  - Sales by Country (map)  
  - Monthly Sales Trend (line chart)  
  - Top 10 Products by Revenue (bar chart)  

- **Customer Dashboard**  
  - Sales by Gender  
  - Sales by Age Group  

- **Profitability Dashboard**  
  - Effect of Discount on Sales  
  - Top Customers (Pareto 80/20 rule)

## 🔹 Part C: Power BI Dashboards  
Designed business-focused BI report with:  

- **Card Visuals**: Total Sales, Total Quantity Sold  
- **Charts**: Sales by Category, Monthly Sales, Sales by Gender, Sales by Age Group, Sales by Country  
- **Interactive Slicers**: Year and Product Category
- https://github.com/Afsana457/Big-Data-Analytics-Project/blob/main/Big%20Data%20Project1.pbix

## 🚀 Key Insights  
- **Discounts** increase sales but reduce profitability when overused.  
- **Pareto principle (80/20)** holds true: a small group of customers drive the majority of revenue.  
- **Country & Gender analysis** show diverse buying patterns, useful for targeted marketing.  

---
## 📊 Dashboards  

### Tableau – Sales Dashboard  
![Sales Dashboard](Sales%20Dashboard.PNG)  

### Tableau – Customer Dashboard  
![Customer Dashboard](Customer%20Dashboard.PNG)  

### Power BI – Profitability Dashboard  
![Power BI Dashboard](Power%20Bi%20Dashbaord.PNG)  
👉 [Download PBIX File](Big%20Data%20Project1.pbix)  


## 💡 Tools Used  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Tableau** (storytelling dashboards)  
- **Power BI** (executive reporting)  
