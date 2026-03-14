# 💳 Credit Card Financial Dashboard

## 📊 Project Overview
An interactive 2-page financial dashboard built using **SQL** and **Power BI** to analyze credit card transaction data and customer behavior patterns.

---

## 🛠️ Tools & Technologies
- **SQL** — Data extraction and transformation
- **Power BI** — Data visualization and dashboard design
- **DAX** — Calculated measures and KPIs

---

## 📁 Dataset
- **Database:** `ccdb` (MySQL)
- **Tables:**
  - `credit_card` — Transaction data
  - `customer` — Customer demographic data
- Data includes credit card transactions, customer demographics, and financial metrics

---

## 📄 Dashboard Pages

### Page 1 — CC Transaction Report
- **KPIs:** Total Revenue (55.3M), Total Interest (7.8M), Transaction Amount (44.5M), Transaction Count (656K)
- **QTR Revenue and Transaction Count** — Quarterly performance chart
- **Revenue by Expenditure Type** — Bills, Entertainment, Fuel, Grocery, Food, Travel
- **Revenue by Education Level** — Graduate, High School, Post Graduate, etc.
- **Revenue by Card Category** — Platinum, Gold, Silver, Blue
- **Revenue by Use Chip** — Swipe, Chip, Online
- **Revenue by Customer Job** — Business, White-collar, Self-employed, Govt, Blue-collar, Retirees

### Page 2 — CC Customer Report
- **KPIs:** Revenue (55.3M), Total Interest (7.8M), Income (575.9M), CSS Score (3.19)
- **Revenue by Week** — Weekly trend analysis (Jan–Oct 2023)
- **Revenue by Age Group** — 20-30, 30-40, 40-50, 50-60, 60+
- **Top 5 States** — TX, NY, CA, FL, NJ
- **Revenue by Marital Status** — Married, Single, Unknown
- **Revenue by Income Group** — High, Medium, Low
- **Revenue by Dependent** — 0 to 4 dependents
- **Revenue by Education** — Detailed education breakdown

---

## 🔍 Key Insights
- **Blue card** generates the highest revenue among all card categories
- **Bills and Entertainment** are the top expenditure types
- **Businessmen** contribute the highest revenue by job category
- **Married customers** generate more revenue than single customers
- **High income group** has the highest transaction volume
- **Q3** shows peak quarterly performance

---

## 🎯 Features
- ✅ Quarter filter (Q1, Q2, Q3, Q4)
- ✅ Gender filter (M/F)
- ✅ Income level filter (Low, Medium, High)
- ✅ Card category filter (Silver, Blue, Gold, Platinum)
- ✅ Week Start Date slicer
- ✅ Interactive cross-filtering across all visuals

---

## 📸 Dashboard Preview
![CC Transaction Report](cc_transaction_screenshot.png)
![CC Customer Report](cc_customer_screenshot.png)

---

## 🚀 How to Use
1. Clone this repository
2. Setup MySQL database named `ccdb`
3. Import `credit_card` and `customer` tables into the database
4. Open `CreditCard_Dashboard.pbix` in Power BI Desktop
5. Update data source to your localhost MySQL connection
6. Refresh the data connection
7. Explore the dashboard using filters and slicers

---

## 👨‍💻 Author
**Waleed Altaf**
- 📧 Connect on [LinkedIn](https://www.linkedin.com/in/waleed-altaf)
- 💼 Data Analytics Enthusiast

---

## 📌 Tags
`Power BI` `SQL` `Data Analytics` `Financial Dashboard` `Credit Card Analysis` `DAX` `Data Visualization`
