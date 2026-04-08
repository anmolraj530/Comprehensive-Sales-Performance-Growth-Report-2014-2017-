# Comprehensive Sales Performance & Growth Report (2014-2017)

This project contains a Power BI dashboard that analyzes sales performance from 2014 to 2017 across product sub-categories, customer segments, and regions.

Primary report file:
- `Sales Repoart FY 2014 - 17 Dashboard Analysis.pbix`

Dashboard preview:
- `Dashboard.png`

---

## Project Objective

Build an interactive business intelligence dashboard to answer:
- How sales quantity changes year by year
- Which product sub-categories drive the highest order quantity
- Which customer segments contribute most
- Which regions generate the highest profit

---

## Dashboard Analysis (From Current Visuals)

### 1) Quantity by Year
The report shows clear year-over-year growth in quantity:
- **2014:** ~8K (20.02%)
- **2015:** ~8K (21.07%)
- **2016:** ~10K (25.97%)
- **2017:** ~12K (32.94%)

Insight:
- The strongest contribution comes from **2017**, indicating strong growth momentum in the latest year in scope.

### 2) Quantity by Segment
- **Consumer:** ~20K (51.54%)
- **Corporate:** ~12K (30.65%)
- **Home Office:** ~7K (17.81%)

Insight:
- **Consumer** is the dominant segment and should remain the primary focus for demand strategy.

### 3) Profit by Region
- **West:** ~108.42K (37.86%)
- **East:** ~91.52K (31.96%)
- **South:** ~46.75K (16.32%)
- **Central:** ~39.71K (13.86%)

Insight:
- **West** and **East** together generate the majority of profit.  
- **Central** underperforms relative to other regions and may need targeted improvement.

### 4) Quantity by Sub-Category (Ranked Pattern)
Highest-volume sub-categories (left side of bar chart) include:
- Binders
- Paper
- Furnishings
- Phones
- Storage

Lower-volume sub-categories include:
- Supplies
- Machines
- Copiers

Insight:
- The demand mix is concentrated in office and stationery-related categories.

---

## Business Recommendations

1. Protect and grow high-performing regions (**West**, **East**) with retention and upsell campaigns.
2. Launch corrective actions in lower-performing regions (**Central**, **South**) with pricing, assortment, and channel optimization.
3. Increase inventory focus for high-demand sub-categories (Binders, Paper, Furnishings, Phones).
4. Design segment-specific marketing, with strongest budget emphasis on the **Consumer** segment.
5. Set 2018 targets using 2017 growth baseline and monitor monthly trend variance.

---

## Repository Contents

- `Sales Repoart FY 2014 - 17 Dashboard Analysis.pbix` - Main Power BI report
- `Dashboard.png` - Dashboard screenshot/preview
- `README.md` - Project documentation and analysis
- `.gitignore` - Git ignore rules
- `.gitattributes` - Git LFS tracking rules for large binary files

---

## Tools Used

- Microsoft Power BI Desktop
- Data modeling and DAX measures (inside `.pbix`)
- Interactive filtering/slicers (Segment, Ship Mode, Region)

---

## How to Run Locally

1. Install **Power BI Desktop**.
2. Clone this repository.
3. Open:
   - `Sales Repoart FY 2014 - 17 Dashboard Analysis.pbix`
4. Refresh data model if needed.

---


## Known Limitations

- The source transactional dataset files are not currently included as separate CSV/Excel files in this folder.
- This repository currently distributes the analytical model through the Power BI `.pbix` artifact and dashboard preview image.

---

## Future Enhancements

- Add raw source dataset files in a `data/` directory (if shareable).
- Add KPI cards for revenue, profit margin, and YOY growth.
- Add drill-through pages for segment and regional deep dives.
- Publish to Power BI Service and add shared report link.

