 IoT-Energy-Metering-Data-Dashboard
Energy Consumption Dashboard (Power BI)
This project focuses on analysing and visualizing energy consumption patterns across multiple devices, shifts, and time periods using Power BI. The objective is to identify usage trends, peak load hours, and high-consumption devices to support operational efficiency and cost optimization.
The dataset includes timestamped energy consumption data segmented by device category (Motor, HVAC, Lighting), shifts, weekdays/weekends, and hourly usage profiles. Data was processed, cleaned, and modelled in Power BI using DAX measures and calculated fields.
The dashboard is organized into multiple analytical pages:
________________________________________
 1. Usage by Day
Provides insights into how energy consumption varies across different days of the week. It displays:
•	Total consumption by day
•	Average daily consumption
•	Weekday vs weekend comparison
•	Hourly time-series visualization
This helps identify consistent usage patterns and high-load operating days.
<img width="1423" height="803" alt="Screenshot (71)" src="https://github.com/user-attachments/assets/c59da921-5b92-420e-aabc-2f0fb07649de" />


________________________________________
 2. Peak Hours
This page identifies the hours and shifts responsible for the highest consumption. It includes:
•	Peak consumption hour and labelling
•	Hourly consumption curve
•	Consumption by production shift
Shift Timings Used in Analysis:
Shift	Time Window
Shift-1	06:00 — 14:00
Shift-2	14:00 — 22:00
Shift-3	22:00 — 06:00
These timings enable clear segmentation of industrial operational periods and support optimization of load distribution.
<img width="1430" height="800" alt="Screenshot (72)" src="https://github.com/user-attachments/assets/15874340-31bd-4f00-ac5f-577dfaef6e86" />

________________________________________
 3. Devices
This page highlights which types of equipment contribute the most to energy consumption. It includes:
•	Total consumption by device category
•	Average consumption per device
•	Identification of top consuming device category
This enables informed decisions around maintenance, performance tuning, and equipment modernization.
<img width="1424" height="800" alt="Screenshot (73)" src="https://github.com/user-attachments/assets/971748f0-47f2-4494-8a6c-041a820b166a" />

________________________________________
📌 Navigation & UX
A home landing page with custom icons allows smooth, intuitive navigation to each insight page with a single click.
<img width="1424" height="804" alt="Screenshot (70)" src="https://github.com/user-attachments/assets/c9f3e8f7-c1be-44cb-bc5d-700006be8cdb" />

________________________________________
🎯 Outcome & Value
The dashboard enables:

✔ Visibility into peak operational loads

✔ Identification of energy-intensive machines and shifts

✔ Better scheduling decisions to reduce peak costs

✔ Insightful reporting for industrial process optimization

✔ Reduced manual effort through automated data visualization

