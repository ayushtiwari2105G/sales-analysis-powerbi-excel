# 📊 Ayush E-commerce Sales Dashboard (Power BI Project)

## 🚀 Project Overview

This project presents an **interactive E-commerce Sales Dashboard** built using **Power BI**.
It provides insights into sales performance, profit trends, customer behavior, and payment patterns.

The dashboard helps in **data-driven decision making** by visualizing key business metrics in a simple and effective way.

---

## 📷 Dashboard Preview

![Dashboard](https://github.com/ayushtiwari2105G/sales-analysis-powerbi-excel/blob/main/powerBI/Full_Dashboard.png)

---

## 🧰 Tools & Technologies Used

* 📊 Power BI (Dashboard & Visualization)
* 📑 Microsoft Excel (Data Processing)
* ⚡ DAX (Data Analysis Expressions)
* 🔄 Power Query (Data Transformation)

---

## 📂 Dataset Information

The project uses two datasets:

* `Details.csv` → Contains sales details (Amount, Profit, Quantity, Category, etc.)
* `Orders.csv` → Contains order information (Customer, City, Date, etc.)

---

## 📌 Key Features

* 📈 **KPI Cards**

  * Total Sales Amount
  * Total Profit
  * Total Quantity

* 📊 **Visualizations**

  * Profit by Month (Bar Chart)
  * Quantity by Category (Donut Chart)
  * Profit by City
  * Profit by Sub-Category
  * Quantity by Payment Mode

* 🎯 **Filters / Slicers**

  * Quarter-wise filtering
  * City selection

---

## 🧠 Learnings from This Project

* Data cleaning and preprocessing in Excel
* Data modeling and relationships in Power BI
* Creating interactive dashboards
* Writing DAX formulas (e.g., calculated columns like ADV = Amount / Quantity)
* Designing user-friendly visual layouts

---

## 📌 Sample DAX Used

```DAX
ADV = Details[Amount] / Details[Quantity]
```

---

## 📁 Project Structure

```
📦 Ayush-Ecommerce-Dashboard
 ┣ 📂 data
 ┃ ┣ Details.csv
 ┃ ┗ Orders.csv
 ┣ 📂 images
 ┃ ┗ dashboard.png
 ┣ 📄 Ayush Ecommercs Sales Dashboard.pbix
 ┗ 📄 README.md
```

---

## 🔮 Future Improvements

* Add customer segmentation analysis
* Include time-series forecasting
* Create drill-through reports
* Add region-wise performance analysis
* Connect with live database instead of static CSV

---

## 💡 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Load datasets if required
4. Explore interactive visuals

---

## 🤝 Contribution

Feel free to fork this repository and improve the dashboard!

---

## 📬 Contact

**Ayush Tiwari**
For any queries or suggestions, feel free to reach out.

---

⭐ If you like this project, don't forget to star the repository!
