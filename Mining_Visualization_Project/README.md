# Global Mining Assets Analysis

This project explores more than **8,500 mining assets worldwide** to understand how mining activities are distributed across countries, asset types, and primary commodities. It also highlights **energy-transition metals** such as lithium, nickel, cobalt, and copper.

---

## Project Overview

- Identified top countries with the highest number of mining assets  
- Analyzed the distribution of asset types (e.g., Mine, Smelter, Refinery)  
- Highlighted the most common primary commodities globally  
- Created interactive dashboards using **Power BI**  
- Mapped energy-transition metals using latitude and longitude coordinates

---

## Dataset

- Source: Global Mining Dataset  
- Records: ~8,500 assets  
- Key fields: `Country`, `Asset_Type`, `Primary_Commodity`, `Latitude`, `Longitude`

### Data preparation included:
- Standardizing text fields
- Fixing invalid coordinate characters
- Removing rows without usable location data
- Creating a simplified `Main_Asset_Type` column

---

## Dashboards (Power BI)

### **1) Global Mining Overview**
- World map of asset locations
- Top 10 countries
- Asset type filter

### **2) Commodity Overview**
- Top 15 primary commodities
- Treemap distribution
- Country slicer

### **3) Energy Transition Metals**
- Filtered map (lithium, nickel, cobalt, copper)
- Top producing countries
- Commodity breakdown

The `.pbix` file is available in the **dashboards/** folder.

---

## 🔍 Key Insights

- Mines represent the majority of assets in the dataset  
- Coal is the most common primary commodity  
- Mining activity is concentrated in a small group of countries  
- Energy-transition metals are unevenly distributed and strategically important

---

## 🛠 Tools Used

- Power BI Desktop  
- Power Query  
- Python (pandas, matplotlib)

---

## Contact

Created by **Talytha Coimbra Gonçalves**  
🔗 LinkedIn: www.linkedin.com/in/talythacoimbra

Feel free to explore and connect!


