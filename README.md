# Regional Sales Analysis Report

## 1. Summary  
This project analyzed five years of regional sales data across the U.S. to identify growth drivers, evaluate profitability, and provide recommendations for improving performance.  
The findings highlight:  
- Financial volatility  
- Heavy dependence on a few products, customers, and regions  
- Profitability driven more by pricing than sales volume  

---

## 2. Business Problem & Objective  

**Problem:**  
Uneven sales and profit performance across regions, limited visibility into seasonal trends, top-performing products, and channel profitability.  

**Objective:**  
Explore and visualize sales data to uncover patterns, identify key drivers, and recommend data-backed strategies for sustainable growth.  

---

## 3. Data Overview  

- **Sources:** Sales, Products, States, Regions, Customers, Budgets (stored in separate tables)  
- **Initial Issues:** No relationships between tables  

**Preprocessing:**  
- Combined all tables into a single dataset  
- Removed redundant columns, standardized names (lowercase)  
- Kept only relevant columns for analysis  
- Renamed fields for clarity  
- Created new metrics (e.g., `profit`, `profit_margin_pct`)  

**Data Quality:** No missing values or duplicate rows  

---

## 4. Exploratory Analysis & Findings  

### 4.1 Monthly Sales Trend  
- Sales fluctuated between **$21M and $26.5M monthly**  
- Strong peaks observed in **May–June**  
- Sharpest decline occurred in **early 2017**  
- No consistent upward growth trend identified  

### 4.2 Sales Channels  
- **Wholesale = 54.1%** of total revenue (largest contributor)  
- Wholesale + Distributor together = **over 85% of sales** → heavy dependency  
- **Export = 14.6%** (lowest), but strategically important  

### 4.3 Products  
- Top 2 products together account for **>20%** of total revenue  
- Big revenue gap between top products and the rest  
- Bottom 5 products cluster around **$50M–$65M** revenue  
- Profit margins relatively consistent across top products  

### 4.4 Regions & States  
- **West region = highest sales (~$350M)**  
- **Northeast = lowest (~$200M)**  
- **California dominates** all states in both orders and revenue  
- Top states contribute majority of sales → sharp drop after top 2  
- Order value distribution skewed: most **< $100K**, most frequent = **$0–$25K**  

### 4.5 Customers  
- Large revenue disparity across customers  
- Bottom 10 customers = **~$4M–$5M each**  
- Top customers contribute **>2× revenue** of bottom group  
- No clear correlation between revenue and profit margin  
- Most customers cluster in **$6M–$9M revenue, ~40% margin**  

### 4.6 Correlation Analysis  
- **Revenue & Profit:** Strong correlation (**0.87**)  
- **Unit Price & Revenue:** Very strong (**0.91**)  
- **Unit Price & Cost:** Very strong (**0.94**)  
- **Quantity Sold:** Weak correlation with revenue (**0.34**) and profit (**0.30**)  

---

## 5. Key Insights  
- **Volatility:** Sales are unstable, with no long-term upward trend  
- **Dependency:** A few products, customers, and regions drive most results  
- **Profitability Drivers:** Pricing and cost matter more than sales volume  
- **Regional Imbalance:** West outperforms Northeast significantly  
- **Customer Profitability:** Top-line revenue doesn’t always mean higher margins  

---

## 6. Recommendations  
- **Seasonality Management:** Use targeted campaigns to stabilize dips (e.g., April recovery, January amplification)  
- **Product Strategy:** Focus on top-performing products, re-evaluate underperforming SKUs  
- **Channel Optimization:** Expand Export channel (higher margins), reinforce Wholesale with incentives  
- **Regional Strategy:** Replicate West/California model; invest in Northeast turnaround  
- **Customer Approach:** Protect top customers with loyalty incentives; upsell to mid-tier customers  
- **Profit Monitoring:** Track orders below margin thresholds and adjust pricing dynamically  

---

## 7. Power BI Dashboard  
Interactive visuals created for:  
- Monthly sales volatility  
- Channel contribution  
- Regional/state performance  
- Customer and product analysis  

**Filters for drill-down:** region, product, customer  

---

## 8. Conclusion  
The analysis and Power BI dashboard provided a data-driven view of performance across regions, products, customers, and channels.  
By addressing volatility, diversifying revenue sources, and focusing on profitability drivers, the company can move towards **sustainable and balanced growth**.  
