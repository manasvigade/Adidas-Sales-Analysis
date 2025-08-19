# 🏷️ Adidas US Sales Analysis

## 📌 Project Overview
This project analyzes Adidas US sales data to uncover trends in **revenue, profitability, products, regions, and sales methods**.  
The goal is to demonstrate end-to-end **data cleaning, analysis, visualization, and business insights** — making it portfolio-ready for data analyst roles.  

---

## 📂 Dataset Information
- **Source:** Adidas US Sales Dataset (Excel)
- **Rows:** ~9K transactions  
- **Columns:**
  - `Retailer`, `Retailer ID`
  - `Invoice Date`, `Region`, `State`, `City`
  - `Product`, `Price per Unit`, `Units Sold`
  - `Total Sales`, `Operating Profit`, `Operating Margin`
  - `Sales Method`

---

## ⚙️ Tools & Libraries
- **Python:** Pandas, NumPy, Matplotlib 
- **Power BI** for dashboarding  
- **GitHub:** version control & project hosting  

---

## 🧹 Data Preparation
1. Handled missing values in numeric columns.  
2. Converted `Invoice Date` to datetime format.  
3. Extracted additional features:
   - `Year`, `Month`, `Quarter`, `Month Name`  
4. Cleaned numeric columns (`Price per Unit`, `Units Sold`, `Total Sales`, `Operating Profit`).  

---

## 🔍 Exploratory Data Analysis (EDA)

### 📊 1. Summary Statistics
- Median **Total Sales:** Provided as baseline comparison  
- Median **Operating Profit:** To evaluate profitability spread  

---

### 🌎 2. Sales & Profit by Region
- **Top Region by Sales:** West → **$269,943,182**  
- **Insight:** West drives the highest revenue but must be benchmarked against profit margin.  

📌 *File:* `region.png`  

---

### 👟 3. Top 10 Products
- **Top Product by Sales:** Men’s Street Footwear → **$208,826,244**  
- **Insight:** Street footwear dominates sales; portfolio diversification can reduce dependency.  

📌 *File:* `products.png`  

---

### 🛒 4. Sales by Method
- **Top Channel by Sales:** In-store → **$356,643,750**  
- **Insight:** In-store sales dominate, but online growth potential should be explored.  

📌 *File:* `sales_method.png`  

---

### 📅 5. Monthly Seasonality
- **Peak Sales Month:** July (Month 7)  
- **Insight:** Strong seasonality, likely linked to back-to-school / summer demand.  

📌 *File:* `monthly_sales.png`  

---

### 🔗 6. Correlation Analysis
- **Correlation (Price vs Units Sold):** +0.27 → weak positive  
- **Insight:** Price does not strongly dictate demand; other factors (marketing, promotions) matter.  

📌 *File:* `heatmap.png`  
 

---

## 📈 Business Insights
1. Focus marketing spend in the **West region** to maximize revenue.  
2. Expand **online channel** to diversify beyond in-store dominance.  
3. Promote **high-margin products** alongside top-selling footwear.  
4. Leverage **seasonal spikes (July)** with targeted promotions.  

---


