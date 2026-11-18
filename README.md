# Financial Data Analysis — Executive Excel Dashboard

## 📌 Project Overview
This project transforms raw multi-year corporate financial records (`Financials.xlsx`) into an interactive, executive-ready Excel dashboard. Built as part of a **Big Data Analytics Capstone**, the objective is to evaluate revenue, profitability, and unit sales across market segments, geographic regions, product lines, and time periods to support strategic management decisions.

---

## 🎯 Business Objectives
Management required visibility into key financial performance drivers across 2013 and 2014:
1. **Segment Performance:** Profit and Gross Sales per market segment.
2. **Geographic Performance:** Profit, Gross Sales, and Units Sold per country.
3. **Annual Growth:** Year-over-Year (YoY) Profit and Gross Sales comparison (2013 vs. 2014).
4. **Product & Regional Mix:** Gross Sales and Profit breakdown per product across countries, segments, and years.

---

## 📊 Executive Summary & Key Metrics
Across the 2013–2014 operating period (700 valid transactions), the business achieved the following top-line results:
* **Total Gross Sales:** $127,931,598.50
* **Total Net Sales (After Discounts):** $118,726,350.26
* **Total Net Profit:** $16,893,702.26
* **Total Units Sold:** 1,125,806.00 units

---

## 🔍 Key Analytical Findings & Business Insights

### 1. Segment Profitability & Losses
* **Finding:** The **Government** segment generated **$11.39M in profit** ($56.40M in Gross Sales), accounting for **67.4%** of total company profit. **Small Business** ranked second with **$4.14M in profit** ($45.94M in Gross Sales). Conversely, the **Enterprise** segment recorded a net loss of **-$614,545.60** despite generating **$21.07M in Gross Sales**.
* **Business Impact:** While Government contracts anchor company profitability, Enterprise operations are actively eroding overall margins despite strong top-line revenue volume.
* **Possible Driver:** High manufacturing costs relative to discounted sale prices or aggressive discount bands applied to Enterprise deals.
* **Recommendation:** Management should conduct a granular margin and discount audit on the Enterprise segment—specifically evaluating pricing tiers and COGS—before scaling Enterprise sales volume further.

### 2. Year-over-Year (YoY) Growth Trajectory
* **Finding:** Total profit surged by **235.6%**, increasing from **$3.88M in 2013** to **$13.02M in 2014**. Gross Sales grew correspondingly from **$28.56M** to **$99.37M**, while units sold rose from **264,674** to **861,132**.
* **Business Impact:** The business demonstrated substantial operational scaling and market expansion between 2013 and 2014.
* **Possible Driver:** Expanded contract volume across Government and Small Business segments in 2014, though exact quarterly seasonality and marketing spend require additional operational data to confirm causation.
* **Recommendation:** Leadership should benchmark 2014 operational capacity and supply chain readiness to ensure inventory and fulfillment infrastructure can sustain continued volume growth.

### 3. Geographic Market Performance
* **Finding:** **France** generated the highest total profit (**$3.78M**), followed closely by **Germany** (**$3.68M**) and **Canada** (**$3.53M**). Notably, while the **United States of America** led in Gross Sales (**$27.27M**), it ranked fourth in total profit (**$3.00M**).
* **Business Impact:** Higher revenue in the U.S. market is not translating proportionally into bottom-line profit compared to European markets.
* **Possible Driver:** Higher discount rates, differing product mixes, or higher COGS in U.S. transactions.
* **Recommendation:** Management should compare average discount bands and product mix in the U.S. against France and Germany to identify margin optimization opportunities.

### 4. Product Line Leadership
* **Finding:** **Paseo** was the top-performing product across every metric, generating **$4.80M in profit** ($35.61M Gross Sales) and **338,239.5 units sold**—leading profitability in Canada, France, Mexico, and the U.S. **VTT** ($3.03M profit) and **Amarilla** ($2.81M profit) followed as strong secondary contributors, while **Velo** led profit specifically in Germany (**$788,789**).
* **Business Impact:** Paseo serves as the primary revenue and profit engine across most international markets.
* **Recommendation:** Prioritize inventory availability for Paseo across key territories while investigating why Velo outperforms other products in Germany to replicate successful regional sales strategies.

---

## 🛠️ Tools & Technical Implementation
* **Microsoft Excel:**
  * **Data Cleaning & Validation:** Verified data types, isolated summary rows from transactional records, and validated numerical integrity across 700 transactional rows.
  * **PivotTables & PivotCharts:** Built dynamic multi-dimensional aggregations across Segments, Countries, Products, and Years.
  * **Interactive Dashboard Design:** Designed an executive dark-themed dashboard (`Financial Data Analysis`) featuring flat 2D bar, column, and pie charts paired with interactive **Year Slicers** for real-time filtering.

---

## 📁 Repository Structure
* `Financials.xlsx` — Raw financial dataset and complete interactive PivotTable/PivotChart dashboard.
* `README.md` — Project documentation, methodology, and executive business insights.
