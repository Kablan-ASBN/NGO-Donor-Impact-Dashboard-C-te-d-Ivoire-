# NGO Donor & Impact Dashboard (Côte d’Ivoire)

## Overview
This project presents a **donor and impact reporting dashboard** I designed and implemented for **Fondation DMConfection**, a nonprofit operating across four regions in Côte d’Ivoire between **2018 and 2024**.

The organization faced recurring challenges with **inconsistent regional reporting, slow consolidation, and delayed donor updates**. I built a standardized, automated reporting workflow that improved data quality, accelerated reporting cycles, and increased donor trust.

This project reflects **real operational analytics work**, not a demo or tutorial dashboard.

---

## Business Problem
- Four regional teams (Abidjan, Bouaké, San Pedro, Yamoussoukro) submitted data in different formats  
- Manual consolidation caused delays and frequent errors  
- Donor updates were inconsistent and often late  
- Leadership lacked a single, trusted view of performance and impact  

---

## Solution
I designed an end-to-end reporting workflow focused on **consistency, automation, and clarity**:

- **Standardized data collection** using Excel templates with locked KPI fields  
- **Automated calculations and validation** with VBA macros to reduce manual errors  
- **Centralized reporting** through Tableau dashboards for real-time visibility  
- Ensured metrics were **simple, interpretable, and trusted** by non-technical stakeholders  

---

## Impact
- **Donor retention increased by ~20%** over the period  
- **On-time reporting improved to ~95%**  
- Supported consistent donor reporting across **4 regions**  
- Enabled leadership and partners to monitor performance and impact at any time  
- Helped onboard new international donors (including UNESCO in 2023)  

---

## How the Dashboard Was Built

### 1. Data Preparation
- Collected donor, funding, and regional impact data spanning **2018–2024**
- Standardized inputs using Excel templates with predefined KPI definitions
- Implemented validation and auto-calculation using VBA macros
- Consolidated cleaned data into a structured CSV (`NGO_Data_Final.csv`)

### 2. Tableau Setup
- Connected the consolidated CSV as the primary data source
- Created calculated fields for:
  - Donor retention percentage
  - Students supported (cumulative)
  - Funds collected by donor origin (XOF)
- Added filters for **Region** and **Donor Origin** to support drill-down analysis

### 3. Visual Design
The dashboard was intentionally designed to be **clear and accessible** to donors and leadership:

- **Line chart**: Donor retention rate over time, benchmarked against a 75% target  
- **Bar chart**: Funds collected by donor origin (local and international)  
- **Bar chart**: Students supported by region  
- **Scatterplot**: Relationship between funds raised and students supported  

### 4. Automation & Access
- Tableau connected to a centralized SharePoint folder
- Data refreshed automatically as regions submitted updated files
- Stakeholders accessed the dashboard online without manual intervention  

---

## Dashboard Highlights
- **Retention Curve** → Tracks donor retention over time against a target benchmark  
- **Donor Origins** → Shows funding sources (Côte d’Ivoire, France, UNESCO, etc.)  
- **Regional Impact** → Visualizes the number of students supported per region  
- **Impact Scatterplot** → Illustrates how funding levels translate into outcomes  

**Figure:** Donor retention, funding sources, and regional impact overview used for leadership and donor reporting.

![Dashboard](DM_Confection_Financial.jpeg)

---

## Dataset
The dataset (`NGO_Data_Final.csv`) includes:
- Year, Month  
- Region (Abidjan, Bouaké, San Pedro, Yamoussoukro)  
- Donor Origin (Local, International, UNESCO, etc.)  
- Funds Collected (XOF)  
- Students Supported  
- Retention Rate (%)  

---

## Tools Used
- **Excel** → standardized templates and VBA macros for automation  
- **Tableau** → dashboards and stakeholder reporting  
- **CSV** → structured, auditable dataset for reproducibility  

---

## Key Takeaway
The primary value of this project is **not visual complexity**, but **operational reliability**.

By standardizing inputs, automating calculations, and enforcing clear KPI definitions, the organization moved from fragmented reporting to a **single, trusted source of truth** for donors and leadership.

This reflects how analytics delivers value in real organizations:  
**fix the data first, then let the dashboard speak for itself.**
