# Water Supply System Design using WaterGEMS

**Author:** Aiman Afzal
**Course:** Water Supply and Wastewater Engineering (Institute of Environmental Engineering & Research, UET Lahore)

## 📌 Project Overview
This project involves the comprehensive design of a centralized water supply system for **Muslim Nagar Housing Society, Lahore** (an 18-hectare residential area with 416 plots). The objective was to replace inefficient individual tube wells and water tankers with a reliable, 20-year design-life network. 

Two design alternatives were analyzed to determine the most cost-effective and reliable solution:
1.  **Direct Pumping System:** Water is pumped directly into the distribution network.
2.  **Pumping with Overhead Reservoir (OHR):** Water is pumped into an OHR and distributed via gravity.

## 🛠️ Data & Tools
*   **Software:** Bentley WaterGEMS
*   **Design Standards:** WASA (Water and Sanitation Agency) and PHED (Public Health Engineering Department) Punjab criteria.
*   **Key Parameters:** 45 LPCD (Liters per capita per day) + 15% Unaccounted-for Water (UFW).

## ⚙️ Methodology
1.  **Population Projection:** Estimated the current population (4,550) and projected a 20-year future population (7,456) using a 2.5% growth rate.
2.  **Demand Calculation:** Calculated Average Daily Demand (385.8 m³/day) and Peak Hourly Demand (36.23 m³/hr).
3.  **Pump Sizing:** Used the Hazen-Williams equation to calculate head losses and brake horsepower (BHP) for both options (10 HP for direct pumping; 15 HP for OHR).
4.  **Network Modeling (WaterGEMS):** Digitized the society layout, allocated demands to nodes (houses, mosques, schools), and simulated hydraulic behavior to ensure pressure and velocity limits were met.
5.  **Cost Analysis:** Performed a detailed 20-year life-cycle cost analysis including capital, electricity, maintenance, and staffing costs.

## 📊 Key Results & Recommendation
*   **Direct Pumping:** Total 20-year cost of PKR 16.49 Million (Estimated monthly household bill: PKR 139).
*   **Pumping with OHR:** Total 20-year cost of PKR 24.78 Million (Estimated monthly household bill: PKR 211).
*   **Recommendation:** The **Direct Pumping System** was recommended due to its lower capital cost, lower operational energy requirements, and cost-effectiveness, given Lahore's generally stable power supply.

---

## 🖼️ Visuals & Analysis

### 1. Study Area
**Muslim Nagar Housing Society Layout**
<img width="1102" height="844" alt="society_map" src="https://github.com/user-attachments/assets/6318b6a6-8a01-4a7f-95e3-4e02517c704f" />

### 2. Hydraulic Modeling
**WaterGEMS Network Layout (Color-coded by Pipe Diameter)**
<img width="1244" height="885" alt="network_layout" src="https://github.com/user-attachments/assets/4bd35748-bf72-4a3d-985f-d8132c384012" />

**Pressure Pipe Inventory**
<img width="870" height="211" alt="pipe_inventory" src="https://github.com/user-attachments/assets/82dd2d67-14db-494d-b394-9c3c6fe83db7" />

### 3. Pump Curves
**Direct Pumping Pump Curve (Design Flow: 212 gpm)**
<img width="669" height="481" alt="pump_curve_direct" src="https://github.com/user-attachments/assets/d0e79f0f-5f1a-432f-a6f8-b4fceb968d67" />

**Pumping with OHR Pump Curve (Design Flow: 141 gpm)**
<img width="858" height="775" alt="pump_curve_ohr" src="https://github.com/user-attachments/assets/8f088814-1b98-470b-ada3-7d6c9d31b5b1" />


### 4. Economic Analysis
**Final Cost Comparison (Monthly Household Bills)**
<img width="1070" height="131" alt="cost_comparison" src="https://github.com/user-attachments/assets/23411cba-58f4-424f-ba9f-abb86396761c" />


---

## 📁 Full Documentation
👉 **[Click here to view the complete Water Supply Design Report (PDF)](./Water_Supply_System_Design_Report.pdf)**
