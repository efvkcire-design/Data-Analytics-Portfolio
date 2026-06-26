# Data Analytics & Strategic Operations Portfolio
## Erick Vera, MBA | Growth & Performance Strategist 

---
# 📊 Featured Project: Global Compensation Architecture & Pay Equity Model

## Project Overview
An end-to-end global total rewards optimization model designed to manage market benchmarking, standardize job catalogs, and audit internal pay equity for a scaling workforce of 2,500 employees across the US, LATAM, and EMEA. 

This model simulates enterprise workflows found in premium HRIS platforms like Workday, ADP, Deel, and Pave AI to deliver executive-ready workforce analytics.

📥 [**Download the Interactive Excel Compensation Template**](https://github.com/efvkcire-design/Data-Analytics-Portfolio/raw/main/global-compensation-model/Global_Compensation_Plan_Template.xlsx)

---

## Technical & Tool Framework
* **Advanced Excel:** Built automated cross-tab metrics, geographic tier structures, and 25th/50th/90th percentile market bands.
* **Python Data Pipeline:** Ingested external market data utilizing the Levels.fyi API, Deel market data, the Bureau of Labor Statistics (BLS), and the South LATAM Salary Benchmark 2026.
* **Advanced Analytics:** Applied Principal Component Analysis (PCA) and Multiple Linear Regression to isolate salary compression and demographic pay gaps.

---

## Executive Deliverables & Data Visualization

To make this complex workforce data actionable for executive leadership, I built a multi-panel visual reporting suite:

### 1. The Executive Summary Dashboard
This 4-panel dashboard transforms raw payroll rows into instant corporate insights.

![Executive Compensation Dashboard](https://github.com/efvkcire-design/Data-Analytics-Portfolio/raw/main/global-compensation-model/executive_compensation_dashboard.jpg)

* **Regional Purchasing Power:** Normalizes global salaries using local cost-of-living index multipliers, proving how baseline pay stacks up from Brazil to the UK.
* **Gender Pay Parity:** Tracks the distribution of Purchasing Power Parity (PPP) across 9 distinct business departments, sorted by gender to easily check for systemic pay gaps.
* **Salary Band Distribution:** A classic statistical boxplot showing our corporate pay architecture. It proves that salary ranges scale upward predictably at each promotion tier (Levels 1, 2, and 3) with zero overlap anomalies.

### 2. Advanced Outlier Target Map
Instead of searching row-by-row for compensation errors, I applied Principal Component Analysis (PCA) to condense multiple factors (like tenure, level, and salary) into a 2D map. 

![PCA Compensation Topology Map](https://github.com/efvkcire-design/Data-Analytics-Portfolio/raw/main/global-compensation-model/pca_compensation_topology.jpg)

* **The Horizontal Axis (PC1):** Tracks standard career maturity. You can see entry-level employees on the left, moving across to executives on the far right.
* **The Vertical Axis (PC2):** Captures internal structural deviations. 
* **The Takeaway:** Any dot floating far below or above its main career group highlights an immediate structural anomaly, severe salary compression, or a pay equity issue that requires manual HR review.

---

## Core Methodologies Implemented
1. **Structural Segmentation:** Separated diverse talent profiles—such as specialized design engineers requiring tech-market rates vs. operational or manufacturing teams requiring localized hourly structures—into clean job families.
2. **Purchasing Power Parity (PPP):** Implemented a cost-of-living multiplier formula to normalize cross-border currency values and ensure equitable baseline tracking across international hubs.
3. **Job Catalog Standardization:** Consolidated 9 separate corporate functions down to clear, uniform Level 1, 2, and 3 career progression tiers.
---
#### 📊 [HR Churn & Workforce Strategy](https://github.com/efvkcire-design/Data-Analytics-Portfolio/tree/main/)

* **Focus:** Sentiment Analysis, Financial Risk Modeling, and Retention Strategy.
* **Strategic Impact:** Identified a $335.8M financial exposure and developed a 90-day roadmap to reduce attrition by 20%.
* **Key Files:** [Interactive Workforce Report (Live View)](https://efvkcire-design.github.io/Data-Analytics-Portfolio/HRChurnStrategy.html) | [People Insights Presentation (Download)](https://github.com/efvkcire-design/Data-Analytics-Portfolio/blob/main/HR_People_Insights_2025_2026%20(1).pptx)

**Presentation Preview:**
<p align="center">
  <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRrUAZ1PPV-5YbaR4z5v-SpA4sLlXVRvVuT8CiH8iSE-r2PJvWIsBauHe9y1CIS541Nq_moPc-qdqa-/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="100%" height="450" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</p>

### 📂 Project Portfolios

#### 📈 [customer segmentation](https://github.com/efvkcire-design/Data-Analytics-Portfolio/tree/main/customer%20segmentation)

* **Focus:** K-Means, RFM Analysis, and PCA.
* **Strategic Impact:** Identified "At-Risk" vs. "High-Value" segments to optimize marketing spend.
* **Key Files:** [Retail Productivity Analysis (Live View)](https://efvkcire-design.github.io/Data-Analytics-Portfolio/customer%20segmentation/RetailStores_Productivity_Sales.html) | [Strategic Report (PDF)](https://github.com/efvkcire-design/Data-Analytics-Portfolio/blob/main/customer%20segmentation/ShopNow_Clustering_CustomerSegmentation_Report.pdf)

#### 🧠 [sentiment analysis](https://github.com/efvkcire-design/Data-Analytics-Portfolio/tree/main/sentiment%20analysis)

* **Focus:** VADER and HuggingFace Transformers.
* **Strategic Impact:** Tripled the recall rate of purchase predictions by integrating customer feedback.
* **Key Files:** [Vader Sentiment Analysis (Live View)](https://efvkcire-design.github.io/Data-Analytics-Portfolio/sentiment%20analysis/ShopNow_VaderSentiment.html) | [HuggingFace Comparison (Live View)](https://efvkcire-design.github.io/Data-Analytics-Portfolio/sentiment%20analysis/ShopNow_HuggingFace.html) | [Sentiment Report (PDF)](https://github.com/efvkcire-design/Data-Analytics-Portfolio/blob/main/sentiment%20analysis/ShopNow_Sentiment%20AnalysisReport.pdf)

#### ⚙️ [strategic reporting](https://github.com/efvkcire-design/Data-Analytics-Portfolio/tree/main/strategic%20reporting)

* **Focus:** Difference-in-Differences and Tableau Visualization.
* **Strategic Impact:** Quantified a 9.5-minute daily engagement boost from early app access.
* **Key Files:** [Product Launch Analysis (Live View)](https://efvkcire-design.github.io/Data-Analytics-Portfolio/strategic%20reporting/Project1TechProProductLaunch.html) | [TechPro Launch Report (PDF)](https://github.com/efvkcire-design/Data-Analytics-Portfolio/blob/main/strategic%20reporting/Project%20TechProProductLaunch_vera4.pdf)

#### 🔮 [predictive modeling](https://github.com/efvkcire-design/Data-Analytics-Portfolio/tree/main/predictive%20modeling)

* **Focus:** Linear & Logistic Regression, KNN.
* **Strategic Impact:** Built a Spotify success model ($R^2=0.212$) to prioritize talent spend.
* **Key Files:** [Spotify Artist Success (Live View)](https://efvkcire-design.github.io/Data-Analytics-Portfolio/predictive%20modeling/SpotifyArtistSuccess.html)
