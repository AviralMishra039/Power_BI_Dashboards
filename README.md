# 💼 Data Jobs Dashboard (Power BI Project)


## 📊 Overview

This project is an interactive Power BI dashboard designed to analyze the global job market in the field of data science and analytics. It presents insights into job trends, salaries, job distribution, and work-related benefits across various data-related roles.

The dashboard allows users to explore job statistics at both high-level and granular (job title-specific) views using **drill-through functionality**, **KPI visuals**, and **custom tooltips**.


### Page 1: High-Level Market View

![Dashboard Page 1](/images/ss1pg1.png)

This is your mission control for the data job market. It showcases key KPIs like total job count, median salaries, and top job titles to give you a quick understanding of what's happening in the job market at a glance.

### Page 2: Job Title Drill Through

![Dashboard Page 2](/images/ss2pg2.png)

This is the deep-dive page. From the main dashboard, you can drill through to this view to get specific details for a single job title, including salary ranges, work-from-home stats, top hiring platforms, and a global map of job locations.

---

## 📌 Features

- **Global Job Insights**
  - Total job count
  - Salary statistics (hourly & yearly)
  - Job counts by title
  - Job distribution by platform and location

- **Drill-Through Page** (per job title)
  - Salary ranges (donut/gauge visuals)
  - Work-from-home percentage
  - Health insurance inclusion
  - Degree requirement mention
  - Job schedule types (full-time, contractor)
  - Job platform breakdown

- **Interactive Visuals**
  - Line charts for job trends
  - Scatter plot of hourly vs median salary
  - Treemap for job schedule distribution
  - World map of job availability

- **UX Features**
  - Clean, minimalistic layout
  - Iconic back navigation
  - Tooltip-enabled insights
  - Consistent color theme with emphasis on contrast

---
## Conclusion

This dashboard showcases how Power BI can transform raw job posting data into a powerful tool for career analysis. It allows users to slice, filter, and drill through data to make informed decisions about their career paths.


## 📂 Dataset

The project uses a dataset (available via Luke Barousse’s GitHub/Google Drive) containing scraped job postings across multiple platforms in the year 2024. It includes:
- Job title
- Salary estimates
- Country and coordinates
- Job platform
- Benefits like remote work and health insurance


---

## 🛠 Skills Learned
- ⚙️ Data Transformation (ETL) with Power Query:** Cleaned, shaped, and prepared the raw data for analysis by handling blanks, changing data types, and creating new columns.

-   **🧮 Implicit Measures:** Formulated measures to derive key insights and KPIs like `Median Yearly Salary` and `Job Count`.
-   **📊 Core Charts:** Utilized **Column, Bar, Line,** and **Area Charts** to compare job counts and track trends over time.
-   **🗺️ Geospatial Analysis:** Leveraged **Map Charts** to visualize the global distribution of jobs.
-   **🔢 KPI Indicators & Tables:** Used **Cards** to display key metrics and **Tables** to provide granular, sortable data.
-   **🎨 Dashboard Design:** Designed an intuitive and visually appealing layout, exploring both common and uncommon chart types to best tell the data story.
-   **🖱️ Interactive Reporting:**
    -   **Slicers:** To dynamically filter the report by Job Title.
    -   **Buttons & Bookmarks:** To create a seamless navigation experience.
    -   **Drill-Through:** To navigate from a high-level summary to a contextual, detailed view.
---



## ✅ How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Use the slicers to filter job titles and observe changes across visuals.
3. Click on a job title to drill through to the detailed view.
4. Hover over visuals for tooltips or explore global maps for geo-distribution.

---


## 🙋‍♂️ Author

**Aviral Mishra**  
[LinkedIn Profile](https://www.linkedin.com/in/aviral-mishra-138237338/)

