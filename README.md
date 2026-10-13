<div align="center">

  <!-- 🌌 ELEGANT DEEP DARK NEON BANNER (WITHOUT DEPI) -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=090b10&customColorList=1&height=210&section=header&text=STORE%20SALES%20DATASET%20ANALYSIS&fontSize=38&fontAlignY=42&fontColor=00F5FF&stroke=00F5FF&strokeWidth=1" width="100%" alt="Header Banner" />

  <!-- TECH STACK DIRECTLY UNDER BANNER -->
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
> An end-to-end enterprise Business Intelligence solution engineered exclusively within the **Microsoft Power BI** ecosystem for the **Digital Egypt Pioneers Initiative (DEPI)**. This project transforms raw transactional store sales data into an interactive, executive-ready decision support system—strictly leveraging native Power Query (M) transformations, Star Schema relational architecture, advanced DAX measure branching, and modern UI/UX canvas engineering.

<br>

## 🧬 SQUAD ARCHITECTURE & DELIVERABLES

---

> [!TIP]
> ### 01. ABDALLAH ELSAYED
> ![](https://img.shields.io/badge/Module-Relational_Data_Modeling_&_Architecture_[Model_View]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Star Schema Engineering:** Architected a high-performance dimensional model separating high-granularity transactional retail records (*Fact_Sales*) from normalized lookup entities (*Dim_Store*, *Dim_Product*, *Dim_Date*, *Dim_Customer*).
> * **Cardinality & Integrity Enforcement:** Configured strict **1:\*** relationships using surrogate and natural keys, eliminating ambiguous paths and preventing many-to-many bottlenecks.
> * **Filter Propagation Optimization:** Enforced single-directional cross-filtering to maximize VertiPaq storage engine compression and guarantee predictable DAX evaluation contexts.

<br>

> [!TIP]
> ### 02. YOUSSEF EHAB
> ![](https://img.shields.io/badge/Module-Automated_ETL_&_Data_Cleansing_[Power_Query_Editor]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Programmatic M-Code Pipelines:** Engineered automated, repeatable data transformation workflows to ingest, normalize, and reshape raw store sales files without manual intervention.
> * **Strict Type Casting & Schema Standardization:** Standardized column data types across dates, currencies, and whole numbers to optimize memory footprint.
> * **Resilient Error Handling & Null Imputation:** Implemented defensive M-script steps to trap parsing errors, strip whitespace, deduplicate records, and apply domain-accurate imputation for missing fields.

<br>

> [!TIP]
> ### 03. ABDALLAH MOHAMED
> ![](https://img.shields.io/badge/Module-Data_Profiling_&_Audit_[Power_Query_Diagnostics]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Full-Dataset Quality Auditing:** Executed diagnostic sweeps using Column Quality and Column Profile engines to quantify valid, error, and empty ratios prior to model load.
> * **Statistical Distribution Analysis:** Evaluated unique value distributions across store branches, product SKUs, and promotional tiers to verify primary key candidacy.
> * **Anomaly & Outlier Detection:** Flagged extreme pricing outliers, negative quantity entries, and chronological gaps in historical sales logs.

<br>

> [!TIP]
> ### 04. MOHAMED ABDELMONEM
> ![](https://img.shields.io/badge/Module-DAX_Calculation_Engine_&_KPIs_[DAX_Engine]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Dynamic KPI Measure Branching:** Authored context-aware DAX measures for Gross Revenue, Net Profit Margin, ABV, and Inventory Turnover using `CALCULATE`, `FILTER`, and iterator functions.
> * **Advanced Time Intelligence Suite:** Built a dedicated date-driven layer tracking **YTD**, **YoY%**, and **MoM%** velocity shifts, rolling averages, and parallel period benchmarks.
> * **Calculation Groups:** Implemented Calculation Groups to dynamically switch metrics and time horizons, drastically reducing measure sprawl.

<br>

> [!TIP]
> ### 05. MOHAMED AHMED
> ![](https://img.shields.io/badge/Module-Dashboard_UI/UX_&_Canvas_[Report_Canvas]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Visual Hierarchy & Grid Architecture:** Designed an intuitive Z-pattern executive layout featuring high-contrast typography, semantic color coding, and balanced whitespace.
> * **App-Like Navigation:** Engineered seamless user journeys utilizing custom Bookmarks, Synced Slicer panels, and dynamic show/hide filter drawers.
> * **Contextual Drill-Throughs:** Built dedicated destination pages and custom micro-chart report tooltips that surface granular store/SKU diagnostics on hover.

<br>

> [!TIP]
> ### 06. MOHAMED YASSER
> ![](https://img.shields.io/badge/Module-Commercial_Insights_&_Strategic_Synthesis_[Storytelling]-1E293B?style=flat-square&labelColor=0F172A)
>
> * **Analytical Storytelling:** Translated complex DAX metrics, seasonal decomposition, and regional variance outputs into clear commercial narratives for C-suite stakeholders.
> * **Revenue & Margin Optimization:** Pinpointed underperforming categories, promotional cannibalization, and peak traffic windows to formulate actionable pricing interventions.
> * **Executive Presentation:** Structured the final analytical synthesis deck, bridging technical Power BI discoveries with measurable business ROI.

---

<br>

<div align="right">

**Academic & Technical Mentor**  
### Eng. Mohamed Assem 🎓  
*Digital Egypt Pioneers Initiative (DEPI)*

</div>
