SwiftRoute Logistics Performance Dashboard (Power BI)

A 4-page interactive Power BI dashboard that tracks delivery performance for a logistics company and shows where delays come from across hubs, drivers and vehicles.

Business Problem

Operations teams had no single view of delivery performance and its causes. This dashboard brings on-time delivery, delivery time and customer satisfaction together with hub, driver and fleet metrics, so teams can see where delays start.

Dataset

4 related tables, Jan 2023 - Dec 2024:

Table	Records
Orders	27,979 (27,727 delivered, 252 cancelled)
Hubs	6
Drivers	55
Vehicles	45

Business requirements are described in Business_Requirements.docx.

Dashboard Pages
Overview: on-time %, delayed %, average delivery time, CSAT, month-over-month change
Vehicles: breakdowns by vehicle age and model, status and maintenance alerts
Hubs: hub capacity against orders processed, processing time
Drivers: driver experience against performance rating
Tools & Skills

Power BI | DAX measures | Power Query | Data modeling (4 related tables) | Slicers | Drill-through

Key Findings
Delivery performance: 78.9% of orders were on time and 21.1% were delayed. Average delivery time was about 35.8 hours and average CSAT was 4.17 out of 5.
Delays are network-wide: Every hub had a delay rate between 19.4% and 22.1%, and no single delay reason caused more than about 10.5% of delays. This points to process improvement across the network, not one failing hub.
Fleet risk: Older vehicles had more breakdowns (correlation of about 0.65 between vehicle age and breakdowns), which supports proactive maintenance and replacement planning.
Recommendations
Standardize hub operating processes across all hubs.
Use breakdown history to schedule preventive maintenance and plan vehicle replacement.
