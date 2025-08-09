# 💧 Maji Ndogo Project 

Power BI Project focused on improving water access in underserved areas for a fictional country, 'Maji Ndogo'.

![image](https://github.com/user-attachments/assets/3f1270ec-6254-465b-b184-e5579e82e768)

---

## Project Description

**Purpose:**

The Maji Ndogo Water Access Dashboard was developed to improve visibility into water distribution and infrastructure in underserved communities. The goal was to enable local authorities identify areas with limited water access, prioritize infrastructure improvements, and monitor progress over time. By transforming raw field survey and operational data into clear, interactive visuals, the dashboard empowered stakeholders to make data-driven decisions that directly impact community well-being.

**Technologies Used:**
- **Power BI** - for building interactive dashboards and data visualization.
- **Excel** - for cleaning and organizing survey and operational datasets.

---

## Data and Processing

**Data Source:**

This dataset was provided as part of the **ALX Data Analytics Program** for a capstone project.  
It simulates real-world water access challenges in underserved areas and includes:
- **Community Profiles** - Population, location, and administrative boundaries.
- **Water Infrastructure Data** - Location, type of water source, functionality status of each water source.

Although fictionalized for learning purposes, the dataset is designed to closely mimic actual operational and survey data collected by NGOs and water authorities in rural regions.

**Data Cleaning:**
- **Removing Duplicates** – Identified and removed repeated records.
- **Handling Missing Values** – Addressed null and incomplete entries using appropriate imputation and reference lookups.
- **Standardizing Formats** – Unified data formats to ensure consistency across the dataset.

**Data Modeling:**
- Created **relationships** between tables.
- Applied a **star schema** design to separate fact tables from dimension tables.
- Added calculated measures in DAX to track KPIs such as households served.

**Data Transformations:**
- Calculated Percentage Population with Access to Basic Water
- Calculated Percentage Sources Needing Improvement.
- Calculated Infrastructure Costs & Budgeted Improvement Cost
- Compared actual cumulative spending with the planned budget to monitor financial efficiency.
- Created a KPI to track the number and percentage of infrastructure projects marked as complete.

---

## Dashboard Features

- Overview of water access by region and towns.
- Map showing locations for various regions and towns.
- Cost and budget comparison for each region.
- Trends for spending and project progress over time.
- Filters and slicers to view specific regions and years.
- Drill-throughs for detailed views of selected areas.

---

## Key Insights

- **Basic Water Access:** Only **34%** of the population had access to basic water services, and despite a **64% improvement**, significant access gaps still exist.
- **Budget Allocation:** A total of **$147M** had been allocated for water infrastructure improvements.
- **Province-Wise Observations:** **Kilimani** led in the number of improvements implemented.
- **Improvement Types & Efficiency:** The most common interventions were diagnosing local infrastructure (5,856 instances) and drilling wells (3,379 instances). 
- **Water Source Insights:** **Urban areas** depended on tap-in-home and shared taps whereas **Rural areas** still rely on rivers and wells, highlighting infrastructure disparities.
- **Budget Distribution:** **Sokoto** received the largest share. **Kilimani** and **Hawassa** also had significant allocations. **Akatsi** may have been underfunded compared to population served.
