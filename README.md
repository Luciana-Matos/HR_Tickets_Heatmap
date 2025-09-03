# 🔄 Circular Heatmap for HR Ticket Patterns (2022–2025)

## 📌 Project Origin & Adaptation
This project is inspired by a challenge from the **Workout Wednesday (WOW)** community, created by **Daniel Marsh-Patrick**.  
The original project demonstrated how to build a circular heatmap in Power BI using the **Deneb custom visual**.  

**Deneb** enables users to leverage **Vega and **Vega-Lite** visualization grammars directly within Power BI, unlocking highly customizable visualizations beyond the standard options.  

Building on this foundation, I adapted the original challenge to reflect a Human Resources use case. Instead of weather data, the visualization now tracks HR ticket volumes across years, months, locations, and topics.  

This tool highlights recurring patterns enabling proactive planning, strategic resource allocation, and deeper investigation into demand drivers.

---

## 📂 Repository Contents
- **dataset.csv** → Synthetic HR ticket dataset (2022–2025), generated with Microsoft Copilot to simulate realistic HR ticket patterns.  
  - Years covered: 2022 to 2025  
  - Locations: Salvador and Feira de Santana  
  - HR Topics:  
    - Recruitment & Hiring  
    - Employee Relations  
    - Compensation & Benefits  
    - Training & Development  
    - Leave & Attendance  

- **circular_heatmap.json** → Vega-Lite specification adapted for Deneb  
- **HR_Heatmap.pbix** → Power BI file containing the visualization  

---

## 🔍 Key Insights
- **Leave & Attendance** spikes every **June** in both cities — possibly linked to school holidays or seasonal leave.  
- **Recruitment & Hiring** surges in **January**, suggesting a hiring cycle at the start of the year.  
- **Training & Development** consistently peaks in **September**, aligning with second-semester development goals.  
- In Salvador, **Employee Relations** tickets rise in **December and January**, whereas in **Feira de Santana**, Employee Relations cases are more evenly distributed throughout the year.  


