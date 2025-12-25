# Tracking_customers_shopping
loaded is the project analysis of customer shopping tracking.

##  Overview
This project analyzes customer shopping behavior for a leading retail company.  
The goal is to uncover purchase drivers (discounts, reviews, seasons, payment preferences) and provide actionable insights to improve **sales, customer satisfaction, and loyalty**.

The workflow includes:
- Loading and cleaning data in **SQL Server**
- Running **SQL queries** for exploratory analysis
- Building an interactive **Power BI dashboard**
- Delivering a **report & presentation** with recommendations

---customer-shopping-powerbi/
│
├── data/tracking_customer_shopping.xlsx
│ 
├── sql server/
│   └──tracking_customer_shop data cleaning.sql
│
├── powerbi/
│   └── Tracking custom_shopping dashboard.pbix
│
├── dax/
│   └── kpi_measures.md
│
├── docs/
│   └── tracking customer shopping docx
│
└── README.md
---

##  Dataset - **Dimensions:**
  - Customer Demographics: ID, Age, Gender, Location  
  - Product & Purchase: Item, Category, Size, Color, Season, Purchase Amount  
  - Tracking & Engagement: Frequency, Previous Purchases, Review Rating, Promo Code, Discount, Shipping, Payment Method  

This structure supports analysis of **sales performance, customer behavior, and marketing effectiveness**.

---

## Tools & Technologies
- **SQL Server** – Data loading, cleaning, transformation, queries  
- **Power BI** – Dashboard visualization & insights   

---

## 🔑 Analysis Delivery
1. **Data Preparation (SQL Server)**
   - Load raw dataset
   - Rename columns (snake_case)
   - Handle duplicates & nulls
   - Create new features (e.g., `age_group`)
   - Remove redundancy

2. **Exploratory Analysis (SQL Queries)**
   - Revenue by gender, season, category, shipping type
   - Discount usage and impact on revenue
   - Review ratings by product & category
   - Repeat purchase behavior

3. **Visualization (Power BI Dashboard)**
   - KPI cards: Total Revenue, Customers, Orders, AOV, Repeat Purchase Rate, Avg Review Rating
   - Revenue performance by location, season, category
   - Customer demographics & purchase frequency
   - Payment & shipping preferences
   - Top customers and product trends
  
4. **Reporting**
   - Summarize findings in a clear report

  ---

  ## Dashboard Highlights
- **6 KPI Cards**: Revenue, Customers, Orders, AOV, Repeat Rate, Avg Rating  
- **Revenue Performance**: Location, Season, Category trends  
- **Purchase Behavior**: Age distribution, spend by gender, frequency analysis  
- **Engagement**: Review ratings, discount usage, shipping type impact  
- **Top Customers**: Revenue contribution & loyalty indicators  

---

## Outcomes
Some insights include:
- Discounts and reviews strongly influence repeat purchases  
- Seasonal trends drive category‑specific sales spikes  
- Express shipping correlates with higher average spend  
- Payment preferences vary by demographic group  





