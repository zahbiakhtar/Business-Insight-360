# 📊 Business Insights 360 – AtliQ Hardware

## 🏢 Project Overview
AtliQ Hardware is a rapidly growing global company that sells computers and computer accessories. To stay ahead of competitors and enable data-driven decision-making, AtliQ implemented Power BI analytics for the first time.

The goal of this project is to provide **360-degree business insights** across:
- Finance  
- Sales  
- Marketing  
- Supply Chain  

This dashboard helps leadership make informed decisions by analyzing trends, performance, and profitability across markets and channels.

---

## 🛠️ Tech Stack
- SQL  
- Power BI Desktop  
- Excel  
- DAX Language  
- DAX Studio  
- Power Query (M Language)  
- Power BI Service  
- GitHub & Git LFS  

---

## 🚀 Power BI Skills & Techniques Used
- Project Charter & Requirement Gathering  
- Stakeholder Requirement Analysis  
- Calculated Columns  
- DAX Measures  
- Data Modeling (Snowflake Schema)  
- Bookmarks for Visual Switching  
- Page Navigation using Buttons  
- DIVIDE() function to handle zero-division errors  
- Date Table using M Language  
- Dynamic Titles based on Filters  
- KPI Indicators  
- Conditional Formatting (Icons & Backgrounds)  
- Data Validation  
- Publishing to Power BI Service  
- Scheduled Refresh using Personal Gateway  
- Power BI App Creation  
- Workspace Sharing & Access Permissions  

---

## 📈 Business Terminologies Used

| Term | Meaning |
|------|-------|
| Gross Price | Price before any deductions |
| Pre-Invoice Deductions | Discounts applied before invoicing |
| Post-Invoice Deductions | Discounts applied after invoicing |
| Net Invoice Sale | Sales after all deductions |
| Gross Margin | Profit before operating expenses |
| Net Sales | Revenue after deductions |
| Net Profit | Final business profit |
| COGC | Cost of Goods Sold |
| YTD | Year to Date |
| YTG | Year to Go |
| Direct | Direct sales from company |
| Retailer | Third-party sellers |
| Distributor | Bulk channel partners |
| Consumer | End user |

---

## 🏭 Company Background
AtliQ Hardware operates globally and sells computers and accessories through three channels:
- Retailers  
- Direct Sales  
- Distributors  

The company recently suffered losses after opening a store in the U.S. based on intuition and Excel-based analysis. Since competitors are using advanced analytics, AtliQ decided to build a strong BI team and use Power BI to guide strategic decisions.

---

## 🧭 Project Kick-Off – Key Questions
Before building the dashboard, these questions were clarified:
- What is the objective of this Power BI dashboard?  
- How will success be measured?  
- What is the project deadline?  
- Will stakeholders require previews?  
- What are stakeholder expectations and concerns?  
- Who will use the dashboard?  
- What risks exist?  
- What data sources are needed?  
- Are there design or layout expectations?  

---

## 🗄️ Dataset Understanding

### Dimension Tables
Contain static master data:
- Customers  
- Products  
- Markets  

### Fact Tables
Contain transactional data:
- Sales  
- Forecasts  

---

## 🧩 Database – gdb041

### dim_customer
- 75 customers  
- 27 markets (India, USA, Spain, etc.)  
- Platforms:
  - Brick & Mortar (Offline)  
  - E-commerce (Amazon, Flipkart)  
- Channels:
  - Retailer  
  - Direct  
  - Distributor  

### dim_market
- 27 markets  
- 7 sub-zones  
- 4 regions:
  - APAC  
  - EU  
  - LATAM  
  - NA  

### dim_product
- Divisions:
  - P & A (Peripherals & Accessories)  
  - N & S (Networking & Storage)  
  - PC (Notebook, Desktop)  
- 14 product categories  
- Multiple product variants  

### fact_forecast_monthly
- Forecasted customer demand  
- Used for:
  - Inventory planning  
  - Customer satisfaction  
- Month-level data (start-date only)

### fact_sales_monthly
- Actual sold quantities  
- Same structure as forecast table  

---

## 🧩 Database – gdb056

| Table | Description |
|------|------------|
| freight_cost | Logistics and shipping costs by market |
| gross_price | Product gross prices |
| manufacturing_cost | Cost to manufacture products |
| pre_invoice_deductions | Discounts before invoicing |
| post_invoice_deductions | Discounts after invoicing |

---

## 🔗 Data Import
Data was imported from **MySQL** into **Power BI** using secure database credentials.

---

## 🧱 Data Modeling
A **Snowflake Schema** was used for:
- High performance  
- Clean relationships  
- Scalability  

Good data modeling ensures fast visuals and accurate insights.

---

## 📊 Dashboard Design

Dashboards were created based on stakeholder-approved mockups.

### 🏠 Home Page
A navigation hub with buttons to access each business view.

### 📄 Dashboard Pages
- Info  
- Finance View  
- Sales View  
- Marketing View  
- Supply Chain View  
- Executive View  
- Products  
- Support  

Users can navigate easily using interactive buttons.

---

## 🧩 GitHub Setup
Large Power BI files were uploaded using **GitHub LFS**.

---

## 🏆 Final Outcome
This project delivers a **360-degree business intelligence solution** for AtliQ Hardware, enabling:
- Better financial tracking  
- Customer and product analysis  
- Sales channel optimization  
- Supply chain monitoring  
- Executive-level decision making  
