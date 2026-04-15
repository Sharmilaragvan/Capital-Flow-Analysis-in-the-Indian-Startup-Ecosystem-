<img width="1712" height="803" alt="startup" src="https://github.com/user-attachments/assets/55ac8441-9fed-47dd-ad6e-0d3dde559693" />
# Capital Flow Analysis in the Indian Startup Ecosystem — Power BI Dashboard

 Built an end-to-end Power BI dashboard for 1000+ startup funding records using Power Query for ETL and a star-schema data model; developed DAX measures to compute KPIs — Total Amount Funded, Total Deals, YoY Growth %, Average Deal Size. Identified top investors, leading industries, and funding distribution trends, translating business requirements into dynamic interactive visuals for stakeholder reporting. 


##  Project Overview

This Power BI dashboard provides a comprehensive visual analysis of capital flow across the Indian startup ecosystem. It consolidates funding data, investor activity, deal tiers, and industry performance into a single interactive report — enabling stakeholders to track investment trends, identify high-growth sectors, and benchmark city-level startup activity.


##  Objectives

- Visualize total capital deployed across Indian startups over multiple years (2020–2025)
- Identify top-funded startups, most active investors, and leading cities by funding volume
- Segment deals by tier (Unicorn-Scale, Mega, Large, Mid, Small, Micro) to understand funding distribution
- Compare industry-level performance using YoY growth, total funding, and startup count
- Track funding against same-period-last-year benchmarks and goal attainment



##  Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Total Amount Funded | **$28 Billion** |
| Total Startups | **1,000+** |
| Most Active Investor | **Accel** |
| Total Fund (Same Period Last Year) | **$2.81 Billion** |
| Goal | **$3.7 Billion (–23.97% variance)** |


##  Visualizations Included

### 1. Total Fund by City (Treemap)
Ranks cities by total funding volume. Top cities include **Bengaluru, Delhi, Mumbai, Gurugram, Hyderabad, Ahmedabad, Chennai, Kolkata, Pune,** and **Noida** — with Bengaluru dominating as the startup capital.

### 2. Total Fund by Startups (Horizontal Bar Chart)
Highlights the top 10 funded startups:
- NextSense — $1.00bn
- HomeFoods — $0.92bn
- Unacademy, CoreSpace, NeoSense — ~$0.71bn each
- BharatPe, Lenskart, Housejoy, Bounce, FinSpace — $0.50–0.59bn

### 3. Total Fund by Deal Tier (Column Chart)
Breaks down investments by deal size category:
- **Unicorn-Scale**: $13.6bn (dominant)
- **Mega ($50M–$2...)**: $9.9bn
- **Large ($10M–$5...)**: $3.4bn
- **Mid ($2M–$10M)**: $0.8bn
- **Small ($500K–$2...)**: $0.3bn
- **Micro (<$500K)**: $0.1bn

### 4. Total Investment by Investors (Horizontal Bar Chart)
Top investors by deployed capital:
- Elevation Capital & A91 Partners — $2.4bn each
- Accel — $2.1bn
- Blume Ventures — $2.0bn
- Kalaari Capital — $1.9bn
- Omidyar Network, Mirae Asset, Info Edge — $1.2–1.4bn

### 5. Industry vs Total Funded Amount & Startups (Table)
Cross-industry comparison with YoY growth:

| Industry | Total Funded | Same Period YR | YoY Growth | Total Startups |
|---|---|---|---|---|
| FoodTech | 3bn | 3bn | 0.20 | 80 |
| Retail | 3bn | 2bn | 0.19 | 89 |
| Consumer Electronics | 3bn | 2bn | **0.53** | 87 |
| Mobility | 2bn | 2bn | 0.12 | 86 |
| Media | 2bn | 2bn | 0.08 | 85 |
| HealthTech | 2bn | 2bn | 0.03 | 76 |
| **Total** | **28bn** | **23bn** | **0.22** | **1100** |

### 6. Year Filter (Slicer)
Interactive year slicer (2020–2025) allowing time-based filtering across all visuals.

### 7. Total Fund by Same Period Last Year (Area Chart)
Compares current period funding against last year's baseline with goal variance tracking.



##  Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development & data modeling |
| **DAX (Data Analysis Expressions)** | Custom measures and KPI calculations |
| **Power Query (M Language)** | Data transformation and cleaning |
| **Excel / CSV** | Source data format |



##  Project Structure


📁 Indian-Startup-Capital-Flow/
├── 📊 startup_dashboard.pbix       # Main Power BI file
├── 📁 data/
│   ├── startup_funding.csv         # Raw funding dataset
│   ├── investors.csv               # Investor details
│   └── industry_mapping.csv        # Industry classification
├── 📸 screenshots/
│   └── dashboard_overview.png      # Dashboard preview
└── 📄 README.md


##  Key Insights

- **Consumer Electronics** had the highest YoY growth at **53%**, making it the fastest-growing sector.
- **Bengaluru** remains the top-funded city, reinforcing its status as India's startup hub.
- The **Unicorn-Scale deal tier** accounts for nearly half of all capital deployed ($13.6bn of $28bn).
- **Elevation Capital and A91 Partners** tied as the top investors by volume at $2.4bn each.
- Funding in the current period is **~23.97% below the $3.7bn goal**, suggesting a market correction or deal slowdown.
- Total ecosystem funding grew **~21.7% YoY** ($23bn → $28bn).



##  How to Use

1. Clone or download this repository
2. Open "C:\Users\ASTA\Downloads\startup project last saved.pbix"  in **Power BI Desktop**
3. If needed, update the data source path under **Transform Data → Data Source Settings**
4. Use the **Year slicer** to filter by a specific funding period
5. Hover over charts for detailed tooltips; click to cross-filter other visuals



##  Contact

Feel free to open an issue or reach out if you'd like to collaborate or have questions about the dataset and methodology.


> **Note:** All funding figures are approximate and aggregated for analytical purposes. Data sourced from publicly available Indian startup funding records.


