# 🏢 HR Analytics: Strategic Employee Attrition Dashboard

An end-to-end Business Intelligence project that transforms raw workforce data into actionable human resources insights. This interactive **Power BI Dashboard** identifies the hidden patterns behind employee turnover, empowering leadership to transition from reactive hiring to proactive talent retention.

. ## 💻 Skills
* Power BI * DAX * Power Query * Data Modeling * Data Visualization * Data Cleaning * Data Analysis
  
  ---
## 📊 Core Business Metrics Overview
By isolating the active cohort of employees who have left the organization, the dashboard delivers immediate visibility into high-level retention performance:
* **Total Workforce Scope:** Evaluated an organizational footprint of **1,480 total employees**.
* **Active Headcount Loss:** Isolated an active attrition volume of **238 departures**.
* **Global Attrition Rate:** Formatted and tracked a clear corporate **Attrition Rate of 16.1%**, establishing a vital baseline for organizational health.

---

## 🎯 Executive Business Insights Delivered

### 1. The Mid-Career Retentivity Window (Age 26-35)
* **The Finding:** Visual tracking shows a distinct peak in employee departures within the **26-35 age bracket**.
* **Strategic Impact:** This represents a high-risk loss of institutional knowledge. Because these individuals represent the pipeline for future senior leadership, HR must prioritize mid-level career progression pathways and retention bonuses within this demographic window.

### 2. High-Volume Turnover in Specialized Technical Roles
* **The Finding:** Granular matrix analysis isolates **Laboratory Technicians** (261 total departures) and **Sales Executives** as the roles driving the highest absolute volume of turnover.
* **Strategic Impact:** Blanket, company-wide retention initiatives will be ineffective. Resources and leadership interventions should be micro-targeted specifically toward laboratory workloads and sales commission restructuring to stabilize these volatile departments.

### 3. Competitor Poaching & Market Vulnerability
* **The Finding:** The satisfaction matrix reveals a critical anomaly: **461 exiting employees** rated their job satisfaction at the highest level (**Level 4 - Very High**), completely outpacing those who left due to low satisfaction (Level 1: 293 departures).
* **Strategic Impact:** This proves that attrition is not being driven by toxic internal morale, but by external competitor poaching. Highly satisfied, top-performing talent is walking out the door—likely due to aggressive headhunting and superior compensation structures elsewhere.

### 4. Compensation Suppression Benchmark ($4,813)
* **The Finding:** Streamlined KPI modeling calculates the exact **Average Monthly Income** of exiting employees to be **$4,813**.
* **Strategic Impact:** This $4.8K figure establishes a vital salary threshold. HR can leverage this benchmark to conduct proactive compensation equity reviews for active staff, ensuring top performers are compensated at or above market rate before they are enticed by outside opportunities.

---

## 🛠️ Technical Implementation & UI/UX Optimizations

To ensure corporate-ready delivery and seamless data exploration, the following analytical engineering standards were applied to the Power BI file:
* **Advanced Data Formatting:** Corrected the underlying summarization architecture of the **Avg Salary** metric from a standard `Sum` to an explicit `Average`. Removed automatic numeric rounding (`K`) and integrated localized currency formatting to display a precise, professional value of **$4,813**.
* **Visual Space Maximization:** Reconfigured the categorical Y-axis text constraints on the *Attrition By Job Role* bar chart to expand margins. This completely eliminated truncated data labels (`...`) and ensured full executive readability.
* **Detail Label Clutter Reduction:** Streamlined data label overlapping on the *Attrition By Education* donut chart by adjusting category placements and separating percentages, optimizing the visual layout for immediate part-to-whole scanning.
* **Granular Cross-Filtering:** Configured a dimensional data breakdown matrix crossing Job Roles with explicit Satisfaction Ratings (Likert Scale 1-4) to isolate exact multi-variable problem areas.

---

## 💻 Technical Environment & Files Included
* 📁 `HR ANALYTIC DASHBOARD.Report/` – Contains all customized front-end UI layout structures, themes, visual positions, and cosmetic properties.
* 📁 `HR ANALYTIC DASHBOARD.Dataset/` – Houses the underlying star-schema data model, relationships, and analytical columns.
* 📄 `HR ANALYTIC DASHBOARD.pbip` – The main lightweight Power BI Project entry file optimized for precise GitHub version control tracking.
* 📄 `HR ANALYTIC DASHBOARD.pbix` – The complete compiled binary report file ready for immediate desktop execution.

---

## 📥 How to Explore the Report Locally
1. Ensure you have **Power BI Desktop** installed on your machine.
2. Clone or download this GitHub repository.
3. Open either the `.pbix` file or the `.pbip` project directory.
4. Use the global slicer panels to interactively filter metrics by Gender, Age, and Department segments.

---
### 🤝 Connect with Me
* 💼 **LinkedIn:** www.linkedin.com/in/aswathy-chandran-11a98a212
aswathy-chandran-11a98a212

* ✉️ **Email:** aswathychand9@gmail.cim


---
