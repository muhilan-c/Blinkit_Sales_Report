# 📊 Blinkit Sales Report (Power BI Project)

This project presents an interactive **sales analysis dashboard** for **Blinkit**, a quick commerce grocery delivery platform. Built with **Power BI**, the dashboard enables decision-makers to explore and monitor key performance indicators such as total sales, item distribution, customer ratings, and outlet performance across various regions and outlet types.

---

## 🖼️ Dashboard Preview

![Blinkit Sales Dashboard](./36482d5a-fe13-46e6-bbdb-4fac90c9e190.png)

---

## 📁 Project Structure

Blinkit_Sales_Report/
│
├── Blinkit_Sales_Report.pbix # Power BI report file
├── Blinkit_sales.csv # Raw sales data used in the report
└── README.md # Project overview and usage instructions


---

## 📌 Key Features

- 📈 **Total Sales Overview**: Visual representation of $1.20M in total sales
- 💵 **Average Sales Value**: $141 per transaction
- 📦 **Items Sold**: 8,523 items
- ⭐ **Average Customer Rating**: 3.9
- 🏙️ **Outlet Analysis**: Sales by outlet location (Tier 1, 2, 3)
- 🛒 **Product Insights**: Breakdown by item types and fat content
- 🕒 **Time Series**: Sales trends over the years (2012–2022)
- 🏬 **Outlet Types & Sizes**: Analysis by size (Small, Medium, High) and type (Supermarket, Grocery, etc.)

---

## 🛠️ Tools Used

- 🧠 **Power BI Desktop** – For dashboard design and data visualization
- 📁 **CSV Dataset** – Source of raw sales data
- 📊 **Power Query (M language)** – Data transformation and cleaning
- 🔢 **DAX** – For calculated measures and KPIs

---

## 🚀 Getting Started

### 1. Clone or Download the Repository

<pre> ```bash git clone https://github.com/your-repo/project-name.git cd project-name ``` </pre>

### 2. Open the Power BI Report
- Launch Power BI Desktop
- Open the file Blinkit_Sales_Report.pbix
- Ensure that Blinkit_sales.csv is located in the same folder as the .pbix file
- If not, update the dataset path via:
  Home > Transform Data > Data Source Settings

---

### 📊 Key Insights
 - 🔼 Tier 3 outlets generate the highest revenue ($472.13K)
  
 - 🟢 High-sized outlets perform better in sales volume
  
 - 🍏 Fruits & Dairy are among the top-selling item types
  
 - 🕔 Peak purchase times range between 5 PM to 9 PM
  
 - 🛍️ Supermarket Type1 contributes ~65% of total sales
  
 - 📈 Consistent upward trend observed from 2012 to 2018, peak at $205K

---

### 🔮 Future Enhancements
✅ Add advanced KPIs using DAX formulas

🔄 Connect with real-time APIs or SQL-based databases

☁️ Publish to Power BI Service for web-based access and scheduled refresh
