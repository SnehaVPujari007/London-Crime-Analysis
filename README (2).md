# Advanced Data Management Project  
**Topic:** Analysing Crime Patterns in London  

## 📌 Project Overview  
This project analyses London crime data (2014–2024) to uncover crime patterns, hotspots, and demographic impacts. Using **R, Hive, and Tableau**, we designed a **data warehouse and data mart** to answer business questions, ensuring data quality and validity checks throughout the process.  

## 👥 Team Roles  
- Data Engineering (Hive, ETL/ELT)  
- Data Cleaning & Validation (R)  
- Visualization & Insights (Tableau)  

## ❓ Business Questions  
1. Who are the primary reporters of crime incidents, and how does reporting vary by borough and crime type?  
2. Which communities/demographics experience the highest crime rates, and how do monthly trends evolve?  
3. Which geographic areas should be prioritised for targeted intervention?  
4. When do peak periods for specific crime categories occur?  
5. Where are London’s crime hotspots, and how have they shifted over time?  

## 📊 Data Sources  
- **data.police.uk** – Street-level crime, outcomes, stop & search (2014–2024)  
- **ONS Census Data** – Population estimates at LSOA level  

## 🛠️ Methodology  
- **Data Cleaning & Validation:** R (`is.na`, duplicates check, population counts)  
- **Data Warehouse Development:** Hive (external tables, fact & dimension tables, modular data mart design)  
- **ETL/ELT Process:** HiveQL for schema creation, joins, and transformations  
- **Visualization & Analysis:** Tableau dashboards for answering business questions  

## ✅ Key Findings  
- **Primary Reporters:** British Transport Police (BTP) lead in theft, violence, and sexual offences.  
- **Demographics:** Males most affected by theft; females most affected by violence and sexual offences.  
- **Geographic Hotspots:** Westminster (especially LSOA 023E) is consistently the top hotspot.  
- **Trends:** Crime peaks in early summer (May–July). Theft continues to rise, while sexual offences drop after Feb 2025.  
- **Shifts:** Hotspots stable (Westminster 023E), but low-crime areas shift over time (e.g., Tower Hamlets, Hackney).  

## 📌 Recommendations  
- Prioritise **Westminster** for targeted interventions.  
- Address seasonal spikes with **increased police presence in summer months**.  
- Use a **Snowflake Schema** in future for better scalability and flexibility.  

## 📈 Tools & Technologies  
- **R Programming** (data cleaning, validation)  
- **Apache Hive** (data warehouse, fact/dimension tables, ELT)  
- **Tableau** (dashboards, hotspot analysis, trends visualization)  

## 📚 References  
- Data Source: [data.police.uk](https://data.police.uk/data/)  
- ONS Population Data  
- Various academic and technical references (GeeksforGeeks, MDPI, Springer, etc.)  
