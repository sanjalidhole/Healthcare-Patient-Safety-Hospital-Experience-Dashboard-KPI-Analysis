# 🏥 Patient Safety & Experience Dashboard — KPI Analytics for Lowell General Hospital

**Author:** Sanjali Dhole  
**Role:** Data Analyst | BI & Visualization | Healthcare Analytics  

---

## 📘 Project Overview

This project delivers a **data-driven performance analysis** for **Lowell General Hospital**, focusing on **patient safety, experience, and operational efficiency**.  

Using real healthcare KPI data, the analysis identifies **bottlenecks in hospital performance**, **quantifies their impact**, and provides **strategic, actionable recommendations** to drive measurable improvements in patient outcomes and staff effectiveness.

---

## 🎯 Problem Statement

Lowell General Hospital’s mission is to *“put patients first in everything we do.”*  
Despite extensive data collection, leadership faced persistent challenges in:

1. Managing **bed occupancy** without compromising care quality.  
2. Improving **staff responsiveness** to enhance patient satisfaction.  
3. Reducing **unassisted falls** to ensure patient safety.  

The goal was to develop a **data-backed performance monitoring framework** that reveals interdependencies between these KPIs and uncovers the **root causes impacting patient safety and experience**.

---

## 📊 Key Performance Indicators (KPIs)

| KPI | Formula | Purpose |
|------|----------|----------|
| **Avg. Bed Occupancy Rate** | (Patients in Licensed Beds per Day / Licensed Beds) × 100 | Tracks operational load & resource utilization |
| **Unassisted Fall Rate (per 1,000 patient days)** | (No. of Falls / Patient Days) × 1,000 | Indicates patient safety & care quality |
| **Staff Responsiveness (Top Box Score)** | (% of “Always” responses in HCAHPS survey) | Reflects timeliness & quality of patient support |

---

## 🧾 Dataset Overview

**Data Fields**
- Month (Reporting period)  
- Bed Occupancy Rate (%)  
- Unassisted Fall Rate (per 1,000 patient days)  
- Staff Responsiveness Score (%)  
- Responsiveness Benchmark (Industry standard)  

> **Data Sources:**  
> - National Database of Nursing Quality Indicators (NDNQI)  
> - Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS)

---

## 📈 Analytical Framework

**1️⃣ Data Exploration & KPI Validation**  
- Assessed performance trends against benchmarks (Occupancy ≤85%, Responsiveness ≥65%).  
- Standardized data for month-over-month comparison.

**2️⃣ Statistical Correlation Analysis**  
- Pearson correlation used to understand interdependencies among KPIs.  
- Identified significant positive and negative relationships.  

**3️⃣ Root Cause Identification**  
- Linked occupancy stress with reduced responsiveness and higher fall risk.  
- Built causal flow model:  
  > **High Occupancy → Staff Overload → Slower Response → Increased Fall Rate**

**4️⃣ Dashboard Visualization**  
- Created a Power BI dashboard with trend lines, KPI variance, and correlation heatmaps for clear stakeholder communication.

---

## 🧮 Key Analytical Insights

| Relationship | Correlation (r) | Insight |
|---------------|-----------------|---------|
| Bed Occupancy ↔ Fall Rate | **+0.70** | Higher occupancy strongly predicts more patient falls |
| Bed Occupancy ↔ Staff Responsiveness | **–0.37** | Moderate inverse relation — crowded conditions reduce timely care |
| Staff Responsiveness ↔ Fall Rate | **–0.79** | Strong negative relation — poor responsiveness increases fall risk |

---

## 💡 Insights & Business Acumen

1. **Systemic Overcapacity Pressure**  
   - The hospital consistently operated at **95–100% occupancy**, exceeding the **85% safe threshold**.  
   - This is not a temporary spike but a *chronic operational overload*, creating sustained pressure on staff and care delivery.  

2. **Responsiveness as a Leading Indicator**  
   - A drop in staff responsiveness is the **earliest measurable warning sign** of declining patient safety.  
   - Even a **1% drop in responsiveness** can predict a measurable rise in fall rates the following month.  

3. **High-Performance Months Prove Feasibility**  
   - Months like *Feb 2020 (96% occupancy, 72.75% responsiveness, 1.79 fall rate)* prove that **operational excellence is achievable** with balanced staffing.  

4. **Thin Safety Margin**  
   - Current responsiveness (65.08%) only *barely meets the target* (65%), with **high volatility and no buffer** — a clear early warning of system strain.  

5. **Quantified Business Impact**  
   - A **10% drop in responsiveness** correlates with a **notable increase in fall risk**, directly impacting patient outcomes, liability exposure, and HCAHPS-based reimbursements.  
   - Operational inefficiencies at this scale could result in **avoidable costs and reputational risk** if left unaddressed.  

---

## 🧭 Strategic Recommendations

| Area | Action | Business Outcome |
|-------|---------|------------------|
| **1. Staffing Flexibility** | Add dynamic staffing protocols when occupancy >92% | Improves response time during peak loads |
| **2. Early Warning System** | Create automated alert if responsiveness <66% | Enables proactive managerial intervention |
| **3. Fall Prevention Task Force** | Analyze unit-level causes during high-fall months | Targets root causes beyond staffing |
| **4. High-Pressure Training** | Simulation-based nurse drills | Builds efficiency and confidence under stress |
| **5. Discharge Optimization** | Streamline patient flow to free beds earlier | Reduces occupancy, stabilizes workload |

---

## 🧠 Business Impact Summary

- 📉 **Reduced Fall Rate Risk:** Proactive staffing and alerts can lower fall risk by up to **20–25%**.  
- 📈 **Improved Responsiveness:** Enhances patient satisfaction scores, influencing HCAHPS-linked reimbursements.  
- 🏥 **Operational Stability:** Balanced occupancy reduces staff burnout and turnover risk.  
- 💰 **Financial Efficiency:** Avoids penalties, boosts hospital rating, and improves funding eligibility.  

---

## 🖥️ Tools & Technologies

- **Data Analysis:** Python (Pandas, NumPy), Excel  
- **Visualization:** Power BI / Tableau  
- **Statistics:** Correlation, Trend, and Variance Analysis  
- **Reporting:** PowerPoint, PDF insights report  

---

## 📊 Dashboard Highlights

**Power BI Dashboard Features**
- KPI Cards showing Occupancy, Responsiveness, and Fall Rate performance  
- Variance vs Benchmark color indicators  
- Trend analysis and correlation visualization  
- Interactive filters for monthly comparison  

---

## 🧩 Project Structure

Patient_Safety_Dashboard/
│
├── data/ # Raw & processed KPI dataset
├── notebooks/ # EDA 
├── reports # Complete analysis report
├── dashboard #Power BI charts 
├── images # screenshots
├── README.md # Documentation
└── requirements.txt # (Optional) dependencies


---

## 🧭 Key Takeaway

This project demonstrates how **analytical thinking and business acumen** combine to turn raw healthcare data into **strategic operational insights**.

It emphasizes:
- Translating statistical correlation into **actionable business outcomes**.  
- Designing **early warning systems** for KPI management.  
- Leveraging **data storytelling** to influence leadership decisions.  

---
## 🚀 Future Work Scope

This project establishes a strong foundation for **data-driven hospital performance monitoring**.  
Future enhancements can extend its analytical depth and operational impact:

1. **Real-Time Data Integration**
   - Connect live hospital databases or APIs to automate KPI updates in Power BI.
   - Enable daily or weekly dashboard refreshes for up-to-date insights.

2. **Predictive Modeling**
   - Develop a machine learning model to forecast fall risk and responsiveness decline using historical patterns.
   - Apply regression or time-series forecasting (ARIMA, Prophet) for proactive alerts.

3. **Advanced Statistical Analysis**
   - Perform multivariate regression to quantify how multiple KPIs jointly impact patient outcomes.
   - Introduce control charts or anomaly detection to flag unusual operational behavior.

4. **Patient Experience Deep Dive**
   - Integrate qualitative HCAHPS feedback to link text-based sentiments with quantitative KPIs.
   - Use NLP (Natural Language Processing) for sentiment categorization of patient comments.

5. **Operational Simulation**
   - Build “what-if” scenarios in Power BI or Python to test staffing or occupancy changes before implementation.
   - Support management decision-making through scenario forecasting.

6. **Scalability & Deployment**
   - Convert dashboard into a web-based analytics portal using Streamlit or Flask for multi-departmental access.
   - Host analytics pipeline on cloud platforms (Azure, AWS, GCP) for scalability.

7. **Cross-Hospital Benchmarking**
   - Expand dataset to include multiple facilities and compare performance across hospitals.
   - Identify best practices and industry leaders for data-driven improvement.

---

> **Vision:**  
> To evolve this dashboard into a **real-time, predictive patient safety monitoring system** that empowers hospital leadership to make informed, timely, and impactful decisions improving both patient experience and staff well-being.

## 📬 Contact

**Sanjali Dhole**  
## ✨ Author
**👩‍💻 Sanjali Dhole**  
Data & BI Analyst | SQL | Python | Power BI | Tableau | Excel  
📧 [mailto:sanjalidhole@yahoo.com]  
🔗 [https://www.linkedin.com/in/sanjali-dhole-48326bba/]  
🌐 [https://github.com/sanjalidhole]
💼 Data Analyst | BI & Visualization | Healthcare Analytics  

---

⭐ *If this project inspired you or provided insights, give it a star on GitHub!*
