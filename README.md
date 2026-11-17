<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=090b10&customColorList=1&height=210&section=header&text=SUPERSTORE%20SALES%20BI%20SOLUTION&fontSize=36&fontAlignY=42&fontColor=00F5FF&stroke=00F5FF&strokeWidth=1" width="100%" alt="Header Banner" />

  <p align="center" style="margin-top: -25px;">
    <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=0D1117&labelColor=161B22" alt="Power BI" />
    &nbsp;
    <img src="https://img.shields.io/badge/Power_Query-0078D4?style=flat-square&logo=databricks&logoColor=38BDF8&labelColor=161B22" alt="Power Query" />
    &nbsp;
    <img src="https://img.shields.io/badge/Star_Schema-107C10?style=flat-square&logo=diagram-next&logoColor=4ADE80&labelColor=161B22" alt="Star Schema" />
    &nbsp;
    <img src="https://img.shields.io/badge/DAX-D83B01?style=flat-square&logo=formula1&logoColor=F87171&labelColor=161B22" alt="DAX" />
  </p>

</div>

---

<br>

> [!NOTE]
> ### ⚡ SYSTEM OVERVIEW
> An end-to-end enterprise Business Intelligence solution engineered exclusively within the **Microsoft Power BI** ecosystem for the **Digital Egypt Pioneers Initiative (DEPI)**. Based on the 9,800 transactional records of the **Superstore Sales Dataset**, this system transforms multi-regional retail and commercial operations into an interactive decision support architecture—strictly leveraging native Power Query (M) ETL pipelines, dimensional Star Schema modeling, advanced DAX time intelligence, executive UI/UX canvas engineering, and strategic business diagnostics.

<br>

## 🎯 STAKEHOLDER MATRIX & BUSINESS REQUIREMENTS

---

| Stakeholder Persona | Strategic Business Goals & Focus | Core Metrics & KPIs Tracked |
| :--- | :--- | :--- |
| **Executive Leadership (C-Suite)** | Macro revenue trajectory, regional performance comparison, corporate segment expansion, and strategic action planning. | Total Revenue ($), YoY Sales Growth %, MoM Sales Growth %, Regional Market Share % |
| **Retail & Category Managers** | Product portfolio momentum, sub-category demand patterns, and customer purchase size tiers. | Revenue by Category/Sub-Category, Top SKUs by Sales, Average Order Value (AOV), Order Frequency |
| **Supply Chain & Logistics Lead** | Delivery fulfillment speed, shipping mode distribution, and transit time bottlenecks across states. | Avg Shipping Lead Time (Days), Revenue by Ship Date, Order Volume by Ship Mode |

<br>

## 🗓️ PROJECT LIFECYCLE & PHASING

---

- **Phase 1: Ingestion, Profiling & Data Hygiene:** Extraction of 9,800 records, auditing postal code missingness, date formatting, deduplication, and operational feature engineering via Power Query (M).
- **Phase 2: Relational Dimensional Modeling:** Deconstruction of the flat superstore table into normalized entities (*Dim_Customer*, *Dim_Product*, *Dim_Geography*, *Dim_Orders*, *Dim_Date*) centered around *Fact_Sales*.
- **Phase 3: DAX Computational Architecture:** Modeling context-aware measures in *Dax Measures*, time intelligence branches (YTD, YoY%, MoM%), calculation groups, and order-to-ship fulfillment metrics.
- **Phase 4: Interface, Navigation & Strategic Canvas:** Layout framing, synchronized cross-filtering across regions and segments, dynamic tooltips, drill-through pathways, and a dedicated **Strategic Insights & Action Plan** page.
- **Phase 5: Commercial Synthesis & Handover:** Executive reporting, cross-functional insight synthesis, presentation deck, and project demo video.

<br>

## 🧬 SQUAD ARCHITECTURE & DELIVERABLES

---

> [!TIP]
> ### 01. ABDALLAH ELSAYED
> ![](https://img.shields.io/badge/Module-Relational_Data_Modeling_&_Architecture_[Model_View]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Star Schema Engineering:** Normalized the cleaned flat table into a robust Star Schema separating transactional grain (*Fact_Sales*) from dimensions (*Dim_Customer*, *Dim_Product*, *Dim_Geography*, *Dim_Orders*, *Dim_Date*).
> * **Cardinality & Key Integrity:** Enforced deterministic **1:\*** relationships utilizing business keys and integer surrogate keys (*Geo_SK*, *Product_SK*), resolving ZIP code overlaps and multi-name SKU collisions.
> * **Filter Propagation & Model Hygiene:** Set single-direction cross-filtering rules, configured active/inactive date relationships (*Order Date* vs. *Ship Date*), hid surrogate/foreign keys, and initialized the *Dax Measures* container.

<br>

> [!TIP]
> ### 02. YOUSSEF EHAB
> ![](https://img.shields.io/badge/Module-Automated_ETL_&_Data_Cleansing_[Power_Query_Editor]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Programmatic M-Code Pipelines:** Developed automated ETL pipelines in Power Query to ingest, clean, and reshape the 9,800 Superstore sales records into a 9,799-row staging table.
> * **Data Type Standardization:** Enforced explicit typing across dates (`Order Date`, `Ship Date`), currencies (`Sales`), and 5-digit text-padded geographic identifiers (`Postal Code`).
> * **Missingness & Anomaly Remediation:** Resolved missing postal codes in Burlington (VT), stripped non-breaking whitespace anomalies (`#(00A0)`), and deduplicated multi-line items.

<br>

> [!TIP]
> ### 03. ABDALLAH MOHAMED
> ![](https://img.shields.io/badge/Module-Data_Profiling_&_Feature_Engineering_[Power_Query_Diagnostics]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Full-Dataset Quality Auditing:** Performed exhaustive diagnostics using Column Profile and Column Quality to audit valid vs. null ratios across all 18 attributes.
> * **Cardinality & Anomaly Detection:** Evaluated frequency distributions across Segments and Categories, identifying shared ZIP codes (`92024`), duplicate order lines, and multi-SKU ID collisions.
> * **Operational Feature Engineering:** Engineered derived analytical attributes in Power Query including *Shipping Lead Time (Days)* and *Order Value Tier* (*Small*, *Medium*, *High-Value*) to support fulfillment and deal-size segmentation.

<br>

> [!TIP]
> ### 04. MOHAMED ABDELMONEM
> ![](https://img.shields.io/badge/Module-DAX_Calculation_Engine_&_KPIs_[DAX_Engine]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Commercial & Logistics KPI Modeling:** Formulated business measures in *Dax Measures* including *Total Revenue*, *Total Orders*, *Average Order Value (AOV)*, *Order Frequency*, *Avg Shipping Lead Time*, and *Revenue by Ship Date* (`USERELATIONSHIP`).
> * **Time Intelligence Layer:** Authored dynamic temporal DAX patterns evaluating **YTD**, **YoY%**, and **MoM%** revenue shifts across fiscal periods alongside *Regional Market Share %*.
> * **Calculation Groups:** Created dynamic Metric Switching groups to consolidate visual card representations without DAX measure clutter.

<br>

> [!TIP]
> ### 05. MOHAMED AHMED
> ![](https://img.shields.io/badge/Module-Dashboard_UI/UX_&_Canvas_[Report_Canvas]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Executive & Strategic Canvas Architecture:** Built a multi-page dashboard layout following visual hierarchy best practices, high-contrast dark theme, and a dedicated **Strategic Insights & Action Plan** executive view.
> * **Dynamic Navigation & Smart Narratives:** Implemented Bookmarks and Selection Pane routing for slide-out filter drawers (*Region*, *Segment*, *Ship Mode*) alongside dynamic *Smart Narrative* summary cards.
> * **Contextual Drill-Throughs:** Integrated custom hover tooltips showing SKU breakdowns and regional micro-trends directly over main visualizations.

<br>

> [!TIP]
> ### 06. MOHAMED YASSER
> ![](https://img.shields.io/badge/Module-Commercial_Insights_&_Strategic_Synthesis_[Storytelling]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Commercial Data Storytelling:** Synthesized regional revenue patterns, product category momentum, and seasonal shopping spikes into executive business insights.
> * **Strategic Insights & Action Plan Content:** Authored the diagnostic findings, actionable recommendations matrix, and projected business impact blocks featured on the final **Strategic Insights** dashboard page.
> * **Executive Presentation Deck:** Structured the final PowerPoint slide deck and video presentation script bridging technical metrics to business outcomes.

---

<br>

<div align="right">

**Academic & Technical Mentor**  
### Eng. Mohamed Assem 🎓  
*Digital Egypt Pioneers Initiative (DEPI)*

</div>
