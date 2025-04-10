# IndyGo-Ridership

# 🚍 IndyGo Ridership Dashboard Project - (LINK- https://drive.google.com/file/d/1YYat3H_t9PYhBs8Dp24qfe98pyiPymDB/view?usp=sharing)

This project explores ridership trends for IndyGo, Indianapolis’ public transportation provider, using real-world transit data from 2022 to 2024. The goal is to provide data-driven insights through interactive Power BI dashboards and lay the groundwork for a broader open data platform to support transparency, planning, and research.
---

## 📊 Project Objectives

- Build a **Ridership Dashboard** to support IndyGo’s transparency and data initiatives.
- Provide actionable insights on **how, when, and where** people use IndyGo transit services.
- Enable stakeholders—including transit planners, community members, and researchers—to make **data-informed decisions**.
- Establish a **scalable framework** for future dashboards (e.g., safety, service reliability, customer feedback).

---

## 🔍 Business Questions Answered

1. **What is the total ridership by day, week, or month?**
2. **How does ridership vary across different route categories?**  
   (e.g., by service frequency or rapid transit lines)
3. **What are the ridership trends for specific routes over the past 12 months?**
4. **How does ridership change across different time frames?**  
   (monthly, by bid period, or over the last 5 weeks)
5. **What are the changes in ridership by month, year, or week?**
6. **Which stops experience the highest and lowest ridership?**

---

## 🧠 Key Insights Delivered

- Year-over-year and seasonal ridership changes
- Peak ridership hours and days of the week
- Stop-level heatmaps to identify high- and low-traffic stops
- Route performance by ridership volume
- Impact of service type on overall usage

---

## 🗂️ Dataset Features

| Component                | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| 📍 **GPS Tracker Data**  | Real-time location, arrival/departure, and schedule deviation               |
| 👥 **Passenger Counters**| Boarding and alighting counts at each stop                                 |
| 🗓️ **Schedule Data**     | Planned route/service schedules                                             |
| 📁 **Format**            | CSV files structured as fact and dimension tables                           |
| 🔎 **Granularity**       | Stop-level data                                                             |
| 📅 **Timeframe**         | 2022–2024                                                                   |
| 🧾 **Data Dictionary**   | Descriptions of columns, units, and table relationships                     |

---

## 🧱 Data Model

The data is modeled using a star schema for efficient querying in Power BI:
- **Fact Table**: Contains ride counts, time metrics, boarding/alighting numbers.
- **Dimension Tables**: Route details, stop locations, service categories, and time dimensions.

---

## 🛠️ Tools & Technologies

- **Power BI**: For data modeling, analysis, and dashboard visualization
- **DAX**: For creating calculated measures and KPIs
- **Power Query**: For data transformation and cleaning
- **CSV**: Source format of all raw datasets

---

## 📸 Dashboard Previews

> 🔗 Screenshots of 3 dashboards (stop-level ridership, daily trends, route breakdown,)

> STOP-LEVEL RIDERSHIP 
![WhatsApp Image 2025-04-10 at 19 16 22_be0d578d](https://github.com/user-attachments/assets/4543696c-cd4f-4f49-b291-ddacca2169e7)

> DAILY TRENDS 
>![WhatsApp Image 2025-04-10 at 19 16 50_854ff306](https://github.com/user-attachments/assets/4b8a95a4-6c77-4e56-9a6c-a9998162eaa4)

>ROUTE BREAKDOWN
> ![WhatsApp Image 2025-04-10 at 19 16 36_4c2574e1](https://github.com/user-attachments/assets/61e1634e-dcc6-438b-8dc9-1d06c2f23e3d)


---

## 🚀 Future Directions

- Integration of **real-time data pipelines** using Azure or AWS
- Development of **Service Reliability** and **Customer Feedback** dashboards
- Publishing the dashboard to a public open data portal or app

---

## 📬 Contact

Feel free to connect if you're interested in data analytics, public transit tech, or just want to talk dashboards!

- [LinkedIn](https://www.linkedin.com/in/kinjal-keshri/)

---
