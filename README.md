# Berlin Unemployment Analysis - July 2025:

**Executive Summary:**  
This project analyzes unemployment trends in Berlin  in July 2025, highlighting demographic, district-level, and sectoral patterns. The goal is to provide actionable insights for policymakers, businesses, and recruitment agencies to optimize workforce planning and interventions. Key findings include areas with persistent unemployment risk, demographic groups most affected, and emerging trends that can inform targeted strategies.


---

## Project Overview
- Explore unemployment rates by age, gender, and district.  
- Examine temporal trends to identify shifts in labor demand.  
- Segment districts and populations using clustering techniques.  
- Create clear visualizations for decision-making.

---

## Business Value / Insights
- **Workforce Planning:** Identify high-risk districts and demographics for targeted recruitment.  
- **Policy Guidance:** Inform government and NGO programs to reduce unemployment effectively.  
- **Strategic HR Decisions:** Guide companies in hiring, training, and workforce allocation.  
- **Forecasting:** Predict labor shortages or oversupply by sector or district to support proactive planning.  
- **Operational Efficiency:** Enable data-driven decision-making for labor market interventions.

---

##  Official Dataset:

### Primary Data Source
[Federal Employment Agency Berlin-Brandenburg](https://www.arbeitsagentur.de/vor-ort/rd-bb/statistik)  

| Attribute          | Value                     |
|--------------------|---------------------------|
| Reference Month    | July 2025                |
| Publication Date   | July 29, 2025            |
| Coverage           | 12 Berlin Job Centers    |


---- 

### Data Structure

 BA_Stats_2025-07.xlsx
 
 ├── Metadata (3 tabs)

 ├── Core Data:
  
  │   ├── Gender (Männer/Frauen)
  
  │   ├── Nationality (Deutsche/Ausländer)
  
  │   ├── Age Groups (15-24, 55+)
  
  │   └── Special Categories
  
  └── Methodology (3 tabs)

---- 

###  How to Reproduce

- Clone this repository

git clone https://github.com/Amirabs7/BerlinUnemploymentInsight-2025.git

cd BerlinUnemploymentInsight-2025

- Install required Python packages

pip install -r requirements.txt

- Run the analysis

python analysis.py

---- 



##  Key Visualizations

# Berlin Unemployment Analysis - July 2025:

This project analyzes July 2025 unemployment statistics in Berlin by **age group**, **nationality**, and **gender**, using official data from the Federal Employment Agency.


### **1. Unemployment by Age,Nationality and Gender Group**:
![Unemployment by Age](arbeitlos_Berlin_by_age.png)


---



## Key Findings:

- **Largest unemployed group by nationality**: **German nationals**  — suggesting structural unemployment rather than purely migrant-related factors.
- **Lowest unemployment rate**: **Youth 15–24** — possibly due to active participation in apprenticeships, vocational programs, or education.
- **Gender gap**: Male unemployment is **1.1× higher** than female — may reflect sectoral employment patterns, with men more concentrated in industries facing slowdowns.
- **Aging workforce impact**: Higher unemployment in the 55+ group indicates possible age-related labor market exclusion.

---



##  Author
Amira Ben Salem  
📧 besamira77@gmail.com
