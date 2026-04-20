# 🚴 AdventureWorks Sales Dashboard — Power BI
 
<div align="center">
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
<img src="https://img.shields.io/badge/Dataset-AdventureWorks-7C3AED?style=for-the-badge" alt="AdventureWorks"/>
<img src="https://img.shields.io/badge/Pages-3%20%2B%20Tooltip-8B5CF6?style=for-the-badge" alt="Pages"/>
<img src="https://img.shields.io/badge/Years-2011--2014-0EA5E9?style=for-the-badge" alt="Years"/>
<img src="https://img.shields.io/badge/Status-Completed-16a34a?style=for-the-badge" alt="Status"/>
<br/><br/>
 
<strong>An interactive Power BI sales dashboard built on the AdventureWorks dataset — tracking 1,465 orders worth $33.93M across 8 territories, 4 product categories, and 4 years (2011–2014), with dynamic slicers and a custom tooltip page.</strong>
 
</div>
---
 
## 🗂️ Table of Contents
 
- [Project Overview](#-project-overview)
- [Dashboard Pages](#-dashboard-pages)
- [Key KPIs at a Glance](#-key-kpis-at-a-glance)
- [Slicer Interactions](#-slicer-interactions)
- [Tools & Technologies](#-tools--technologies)
- [Project Structure](#-project-structure)
- [How to Use](#-how-to-use)
---
 
## 🎯 Project Overview
 
This dashboard analyzes the **AdventureWorks** sales database — a widely used Microsoft sample dataset representing a fictional bicycle manufacturer. The report covers:
 
- 📦 **Order performance** across territories and years
- 🚦 **Order status distribution** (Approved, Shipped, Cancelled, etc.)
- 🚲 **Product category demand** (Bikes, Clothing, Accessories, Components)
- 🌍 **Geographic breakdown** across 8 international territories
- 🎯 **Custom tooltip** showing top 5 products on hover
| Feature | Details |
|---|---|
| 📁 Power BI File | `Sales_Dashboard.pbix` |
| 📄 Pages | Tooltip · Page 3 · Page 4 |
| 📅 Date Range | 2011 – 2014 |
| 🌍 Territories | 8 regions worldwide |
| 🏷️ Product Categories | 4 (Bikes · Clothing · Accessories · Components) |
| 📊 Total Orders | 1,465 |
| 💰 Total Due | $33.93M |
 
---
 
## 📑 Dashboard Pages
 
### 🎯 Tooltip Page
> *Custom tooltip that appears on hover — shows top 5 products by quantity*
 
A hidden page used as a **visual tooltip** on the main dashboard. When hovering over territory data, it displays:
 
| Product | Quantity |
|---|---|
| AWC Logo Cap | **2.4K** |
| Long-Sleeve Logo Jersey, L | **2.4K** |
| Classic Vest, S | **2.1K** |
| Short-Classic Jersey, XL | **1.8K** |
| Sport-100 Helmet, Blue | **1.8K** |
 
---
 
### 📊 Page 3 — Main Sales Overview
> *Full overview with all data unfiltered*
 
**KPI Cards:**
 
| KPI | Value |
|---|---|
| 📋 #OrderDetails | **24K** |
| 💰 Total Due | **$33.93M** |
| 🛒 #Orders | **1,465** |
| 💵 SubTotal Amount | **$30.09M** |
| 🚚 Total Freight | **$915.97K** |
| 🧾 Total Taxes | **$2.93M** |
 
**Visuals:**
 
| Visual | Type | Key Insight |
|---|---|---|
| #Orders and Total Due by Territory | Combo Bar Chart | Canada leads with 448 orders & $11.9M |
| #Orders by Year | Line + Area Chart | Peak in 2013 with 708 orders |
| #Orders by Status | Horizontal Bar | Approved (396) · In Process (392) · Shipped (374) |
| Total Quantity by ProductCategory | Treemap | Bikes dominate at 28K units |
 
**Slicers:** Year (2011–2014) · Territory (8 regions)
 
---
 
### 📊 Page 4 — Filtered Territory View
> *Same layout — dynamically updates based on slicer selections*
 
The dashboard responds instantly to slicer changes, enabling territory and year-level analysis.
 
**Example — Northwest + United Kingdom + Central territories:**
 
| KPI | Filtered Value |
|---|---|
| #OrderDetails | 9,502 |
| Total Due | $13.61M |
| #Orders | 651 |
| SubTotal Amount | $12.06M |
| Total Freight | $368.24K |
| Total Taxes | $1.18M |
 
**Example — Canada + France + Germany + Australia (2012–2014):**
 
| KPI | Filtered Value |
|---|---|
| #OrderDetails | 14K |
| Total Due | $19.90M |
| #Orders | 844 |
| SubTotal Amount | $17.64M |
| Total Freight | $537.64K |
| Total Taxes | $1.72M |
 
---
 
## 📊 Key KPIs at a Glance
 
```
┌──────────────────────────────────────────────────────────────┐
│               ADVENTURE WORKS SUMMARY (All Data)            │
├──────────────────────┬───────────────────────────────────────┤
│  📋 Order Details    │  24,000+ line items                   │
│  🛒 Total Orders     │  1,465 orders                         │
│  💰 Total Due        │  $33.93M                              │
│  💵 SubTotal Amount  │  $30.09M                              │
│  🚚 Total Freight    │  $915.97K                             │
│  🧾 Total Taxes      │  $2.93M                               │
├──────────────────────┼───────────────────────────────────────┤
│  🏆 Top Territory    │  Canada (448 orders · $11.9M)         │
│  📅 Peak Year        │  2013 (708 orders)                    │
│  🟢 Top Status       │  Approved (396 orders)                │
│  🚲 Top Category     │  Bikes (28K units)                    │
│  🏅 Top Product      │  AWC Logo Cap & Long-Sleeve Jersey    │
└──────────────────────┴───────────────────────────────────────┘
```
 
### 📦 Product Category Breakdown
 
| Category | Total Quantity |
|---|---|
| 🚲 Bikes | **28K** |
| 👕 Clothing | **17K** |
| 🧢 Accessories | **5K** |
| ⚙️ Components | **5K** |
 
### 🌍 Orders by Territory (Top 5)
 
| Territory | #Orders | Total Due |
|---|---|---|
| 🥇 Canada | 448 | $11.9M |
| 🥈 Northwest | 335 | $6.9M |
| 🥉 France | 188 | $6.2M |
| United Kingdom | 188 | $4.8M |
| Germany | 139 | $2.3M |
 
### 📅 Orders by Year Trend
 
| Year | #Orders |
|---|---|
| 2011 | 84 |
| 2012 | 333 |
| 2013 | **708** ← Peak |
| 2014 | 340 |
 
### 🚦 Orders by Status
 
| Status | Count |
|---|---|
| ✅ Approved | 396 |
| 🔄 In Process | 392 |
| 📦 Shipped | 374 |
| ❌ Cancelled | 137 |
| 🚫 Rejected | 117 |
| ⏳ Backordered | 49 |
 
---
 
## 🎛️ Slicer Interactions
 
The dashboard features **2 cross-filtering slicers** that update all visuals simultaneously:
 
| Slicer | Options |
|---|---|
| 📅 **Year** | 2011 · 2012 · 2013 · 2014 |
| 🌍 **Territory** | Australia · Canada · Central · France · Germany · Northwest · Southwest · United Kingdom |
 
---
 
## 🛠️ Tools & Technologies
 
| Tool | Usage |
|---|---|
| ![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?logo=powerbi&logoColor=black&style=flat-square) | Dashboard design, visuals, slicers, tooltip page |
| ![DAX](https://img.shields.io/badge/-DAX-7C3AED?style=flat-square) | KPI measures (Total Due, SubTotal, Freight, Taxes) |
| ![AdventureWorks](https://img.shields.io/badge/-AdventureWorks-8B5CF6?style=flat-square) | Microsoft sample sales database |
 
---
 
## 📁 Project Structure
 
```
📦 AdventureWorks-Sales-Dashboard/
├── 📊 Sales_Dashboard.pbix        ← Power BI report file
├── 📸 screenshots/
│   ├── 01_Dashboard_All_Data.png
│   ├── 02_Filtered_Northwest_UK.png
│   ├── 03_Filtered_Canada_France.png
│   └── 04_Tooltip_Page.png
└── 📄 README.md
```
 
---
 
## 🚀 How to Use
 
1. Download `Sales_Dashboard.pbix`
2. Open in **Power BI Desktop** (2023 or later)
3. Navigate using the **bottom page tabs**: Tooltip · Page 3 · Page 4
4. Use the **Year slicer** to filter by a specific year
5. Use the **Territory slicer** to filter by one or more regions
6. **Hover** over any bar in the territory chart to trigger the **custom tooltip** showing top 5 products
---
 
## 👤 About the Author
 
**Abd Elfatah Gaber Ebrahim**  
Data Analysis Student · ITI (Information Technology Institute) · Egypt 🇪🇬
 
<div align="center">
<a href="https://www.linkedin.com/in/abd-elfatah-gaber-ebrahim/"><img src="https://img.shields.io/badge/LinkedIn-Abd%20Elfatah%20Gaber-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/></a>
<a href="https://github.com/abd-elfatah-gaber"><img src="https://img.shields.io/badge/GitHub-abd--elfatah--gaber-181717?style=for-the-badge&logo=github" alt="GitHub"/></a>
<a href="https://mostaql.com/u/Abdelfatah26"><img src="https://img.shields.io/badge/Mostaql-Abdelfatah26-1abc9c?style=for-the-badge" alt="Mostaql"/></a>
<a href="https://khamsat.com/user/abd_elfatah_gaber26"><img src="https://img.shields.io/badge/Khamsat-abd__elfatah__gaber26-e67e22?style=for-the-badge" alt="Khamsat"/></a>
 
</div>
---
 
<div align="center">
⭐ <strong>If you found this project useful, please consider giving it a star!</strong> ⭐
 
<em>Built with ❤️ using Power BI · AdventureWorks Dataset</em>
 
</div>
