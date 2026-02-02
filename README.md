# 📊 Electronic Sales Performance Dashboard  
**YTD, YoY & Profit Analysis (2011–2014)**


## Table of Contents

- [Project Background](#project-background)
- [Key Areas of Analysis](#key-areas-of-analysis)
- [Data Source](#data-source)
- [Data Structure & Initial Checks](#data-structure--initial-checks)
- [Data Exploration & Preparation](#data-exploration--preparation)
- [Executive Summary](#executive-summary)
- [Overview of Findings](#overview-of-findings)
- [Insights Deep Dive](#insights-deep-dive)
  - [Sales Performance & Time Trends](#sales-performance--time-trends)
  - [Channel Performance & Growth Momentum](#channel-performance--growth-momentum)
  - [Product Category Contribution & Profitability](#product-category-contribution--profitability)
  - [Geographic (Zone) Performance](#geographic-zone-performance)
- [Recommendations](#recommendations)
- [Assumptions and Caveats](#assumptions-and-caveats)
- [Key Takeaway](#key-takeaway)
- [Author](#author)


## Project Background

The company operates in the **electronics retail industry**, offering a wide range of consumer electronic products across multiple **sales channels** (Store, Online, Reseller, Catalog) and **geographic zones**. Between **2011 and 2014**, the business expanded both its product portfolio and market reach, increasing the need for **structured performance monitoring and profitability analysis**.

As a **Data Analyst embedded within the business**, my responsibility was to help stakeholders understand not only *how much* the company was selling, but **how sales growth translated into profit**, which products were most profitable, and whether growth patterns were **sustainable across time, channels, and regions**.

Existing reporting focused largely on topline revenue, with limited visibility into **margin behavior**, **growth quality**, and **performance drivers**. This project was initiated to close that gap by delivering a **clear, interactive dashboard** that combines **time intelligence, YoY variance, and profitability analysis** in one coherent analytical view.

The dataset used for this analysis can be found here:
[Dataset](<https://github.com/Rofiat-Adebayo/Sales-Performance-Dashboard-Scale-vs-Growth-Analysis/blob/main/Electronic%20Sales_e6c80a7a8f22809f1b33e72ae32f09d4.xlsx>)

Data exploration and validation were performed directly in Power BI and can be reviewed here:  
[Data Preparation & Validation](<https://github.com/Rofiat-Adebayo/Sales-Performance-Dashboard-Scale-vs-Growth-Analysis/blob/main/Electronic%20Sales_e6c80a7a8f22809f1b33e72ae32f09d4.xlsx>)


[View the Interactive Power BI Dashboard](<https://app.powerbi.com/links/LJb5m9s2mq?ctid=37d7521a-5079-48af-9131-4ac2cb6f1e3a&pbi_source=linkShare>)


---

## Key Areas of Analysis

Insights and recommendations are provided across the following areas:

- **Sales Performance & Time Trends**
- **Channel Performance & Growth Momentum**
- **Product Category Contribution & Profitability**
- **Geographic (Zone) Performance**



## Data Source

The dataset represents historical electronic sales transactions covering **2011–2014**, including order-level sales values, quantities, unit costs, product attributes, sales channels, and geographic information. The data was provided in a structured format suitable for business intelligence analysis.


### Data Structure & Initial Checks

The company’s analytical data model is composed of three core tables: **Sales Details**, **Calendar**, and a dedicated **DAX Measures** table. The Sales Details table contains approximately **15,000 transaction-level records**. A description of each table is outlined below:

---<img width="526" height="312" alt="!sales" src="https://github.com/user-attachments/assets/724c72f8-de1b-4097-bf04-b84dc3cf4034" />


## Data Exploration & Preparation

Data exploration, validation, and preparation were carried out directly within **Power BI** to ensure analytical reliability. Key steps included:

- Validating data types, date coverage, and record completeness using **Power Query**
- Cross-checking relationships between sales, quantity, unit cost, and profit
- Creating a centralized **Calendar table** to enable consistent YTD, QTD, and YoY calculations
- Performing DAX-based sanity checks to confirm metric consistency across filters
- Structuring the model into a clean **star schema** to support scalable analysis and interaction logic

All transformations were intentionally kept minimal to preserve data integrity and transparency.

---

## Executive Summary

While overall sales and profit increased during the analysis period, **performance varied significantly across products, channels, and regions**. Some high-revenue areas showed slowing growth, while smaller segments exhibited stronger momentum. Profitability also differed meaningfully by product category, indicating that **not all revenue growth contributed equally to profit**.

This dashboard enables leadership to quickly assess **performance health**, identify **growth opportunities**, and understand **where margin optimization is required**.

<img width="536" height="352" alt="SALES PERFORMANCE" src="https://github.com/user-attachments/assets/20206a59-5c1b-48eb-9105-d87bddd11292" />


## Overview of Findings

1. **Revenue scale and growth momentum are not always aligned**, requiring separate but connected analysis.
2. **Profit margins vary materially by product category**, impacting the quality of revenue.
3. **Regional and channel performance differs**, suggesting the need for targeted strategies rather than one-size-fits-all decisions.


## Insights Deep Dive

### Sales Performance & Time Trends

- Sales demonstrate **clear seasonal patterns**, with peaks toward the latter part of the year.
- YoY indicators reveal periods of slowing growth despite increasing absolute sales.
- Monthly sales and profit trends show divergence in certain periods, highlighting **margin pressure risks**.



### Channel Performance & Growth Momentum

- **Store** remains the largest revenue contributor but exhibits slower growth momentum.
- **Online and Reseller channels** show stronger YoY growth, albeit from smaller revenue bases.
- **Catalog** contributes modest revenue with limited growth impact.

This reinforces the importance of separating **scale (size)** from **momentum (growth)** when evaluating channel performance.


### Product Category Contribution & Profitability

- **Computers and Cameras** generate the highest sales volumes.
- **Profit Margin % analysis** reveals meaningful differences across product categories, with some lower-revenue categories delivering stronger margins.
- High revenue does not always correlate with high profitability, highlighting opportunities for **product mix and pricing optimization**.


### Geographic (Zone) Performance

- The **South East and South South zones** lead in both revenue and units sold.
- Certain zones exhibit high volume but comparatively lower revenue, suggesting **pricing or mix effects**.
- Geographic disparities indicate potential for **localized sales and pricing strategies**.



## Recommendations

Based on the analysis, the following actions are recommended:

- Balance focus between **high-revenue** and **high-growth** channels to sustain long-term performance.
- Incorporate **profit margin analysis** into product-level decision-making, not just revenue metrics.
- Investigate periods of sales–profit divergence to address cost or pricing inefficiencies.
- Optimize regional strategies by aligning product mix with zone-specific demand patterns.
- Use YoY and margin diagnostics as **early indicators**, not just retrospective measures.

---

## Assumptions and Caveats

**Assumptions**
- All transactions are finalized and comparable year-over-year.
- Sales, cost, and margin definitions remain consistent across periods.
- Calendar alignment ensures like-for-like period comparisons.

**Caveats**
- Newly introduced products or channels may distort YoY metrics.
- Partial-period data should be interpreted cautiously.
- One-off events may influence trends in specific periods.

---

## Key Takeaway

This project demonstrates how combining **time intelligence, growth diagnostics, and profitability analysis** within a thoughtfully designed dashboard can transform raw sales data into **actionable business insight**, enabling stakeholders to understand **what is happening, why it is happening, and where to act next**.

---

### Author

**Rofiat Adebayo**  
Data Analyst | Business Intelligence | Analytics & Insights
Connect with me: https://www.linkedin.com/in/rofiat-adebayo/
Contact: 07066609682
