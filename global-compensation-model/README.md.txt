# Global Compensation Architecture & Pay Equity Audit Model

## Project Overview
An end-to-end global total rewards optimization model designed to manage market benchmarking, standardize job catalogs, and audit internal pay equity for a scaling workforce of 2,500 employees across the US, LATAM, and EMEA. 

This model simulates enterprise workflows found in premium HRIS platforms like Workday, ADP, Deel, and Pave AI to deliver executive-ready workforce analytics.

## Technical & Tool Framework
* **Advanced Excel:** Built automated cross-tab metrics, geographic tier structures, and 25th/50th/90th percentile market bands.
* **Python Data Pipeline:** Ingested external market data utilizing the Levels.fyi API, Deel market data, the Bureau of Labor Statistics (BLS), and the South LATAM Salary Benchmark 2026.
* **Advanced Analytics:** Applied Principal Component Analysis (PCA) and Multiple Linear Regression to isolate salary compression and demographic pay gaps.

---

## Executive Deliverables & Data Visualization

To make this complex workforce data actionable for executive leadership, I built a multi-panel visual reporting suite:

### 1. The Executive Summary Dashboard
This 4-panel dashboard transforms raw payroll rows into instant corporate insights.

![Executive Compensation Dashboard](executive_compensation_dashboard.jpg)

* **Top Left (Regional Purchasing Power):** Normalizes global salaries using local cost-of-living index multipliers, proving how baseline pay stacks up from Brazil to the UK.
* **Top Right (Gender Pay Parity):** Tracks the distribution of Purchasing Power Parity (PPP) across 9 distinct business departments, sorted by gender to easily check for systemic pay gaps.
* **Bottom Left (Salary Band Distribution):** A classic statistical boxplot showing our corporate pay architecture. It proves that salary ranges scale upward predictably at each promotion tier (Levels 1, 2, and 3) with zero overlap anomalies.

### 2. Advanced Outlier Target Map
Instead of searching row-by-row for compensation errors, I applied Principal Component Analysis (PCA) to condense multiple factors (like tenure, level, and salary) into a 2D map. 

![PCA Compensation Topology Map](pca_compensation_topology.jpg)

* **The Horizontal Axis (PC1):** Tracks standard career maturity. You can see entry-level employees on the left, moving across to executives on the far right.
* **The Vertical Axis (PC2):** Captures internal structural deviations. 
* **The Takeaway:** Any dot floating far below or above its main career group highlights an immediate structural anomaly, severe salary compression, or a pay equity issue that requires manual HR review.

---

## Core Methodologies Implemented
1. **Structural Segmentation:** Separated diverse talent profiles—such as specialized design engineers requiring tech-market rates vs. operational or manufacturing teams requiring localized hourly structures—into clean job families.
2. **Purchasing Power Parity (PPP):** Implemented a cost-of-living multiplier formula to normalize cross-border currency values and ensure equitable baseline tracking across international hubs.
3. **Job Catalog Standardization:** Consolidated 9 separate corporate functions down to clear, uniform Level 1, 2, and 3 career progression tiers.