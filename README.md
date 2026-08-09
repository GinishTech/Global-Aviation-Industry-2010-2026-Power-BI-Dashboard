# ✈️ Global-Aviation-Industry-2010-2026-Power-BI-Dashboard
End-to-end Power BI project: star-schema data model, DAX measures, and a 6-page interactive dashboard covering the global aviation industry(2010-2026).

## 📊 Overview

This project builds a star-schema data model from five raw datasets
(airline financials, passenger traffic, route performance, fleet orders,
and aviation incidents), connects them through shared date and airline
dimensions, and presents the findings across six interactive report pages.

## 🗂️ Dashboard pages

- 🌍 **Executive Overview** — key KPIs across the industry: revenue,
  passengers, load factor, incidents, and aircraft orders
- 💰 **Financial Performance** — airline revenue, operating margin, and
  year-over-year growth by business model and region
- 🧭 **Global Traffic** — RPK/ASK trends and load factor by region over time
- 🗺️ **Route Performance** — top routes by revenue, corridor breakdown, and
  distance-vs-fare analysis
- 🛩️ **Fleet & Manufacturers** — order and delivery trends by manufacturer,
  book-to-bill ratio
- 🛡️ **Safety & Incidents** — incident counts, severity breakdown, and
  fatality analysis by year and aircraft type

## 🛠️ Tools & techniques

- Power BI Desktop (data modeling, report design)
- DAX (custom measures: YoY growth, book-to-bill ratio, fatal incident rate)
- Power Query / star-schema data modeling
- Custom Power BI theme and iconography

## 🖼️ Dashboard
**1.Executive Overview**

<img width="500" height="350" alt="1" src="https://github.com/user-attachments/assets/9db91676-0377-4baa-8326-4676862d870a" />

**2.Financial Performance**

<img width="500" height="350" alt="2" src="https://github.com/user-attachments/assets/56a13008-c5c2-40d4-b086-fd071fcd2710" />

**3.Global Traffic**

<img width="500" height="350" alt="3" src="https://github.com/user-attachments/assets/bb4105b4-c5cc-4d1d-bf62-f9c8ae0c9d8b" />


**4.Route Performance**

<img width="500" height="350" alt="4" src="https://github.com/user-attachments/assets/cc369c43-adba-495e-aac6-659de410a13a" />


**5.Fleet & Manufacturers**

<img width="500" height="350" alt="5" src="https://github.com/user-attachments/assets/e5f38c64-1c8d-4860-9570-165f88d47930" />


**6.Safety & Incidents**

<img width="500" height="350" alt="6" src="https://github.com/user-attachments/assets/279e263c-e0db-4264-b7a7-c0c0bd28c271" />

## 🔍 Data note

Route and incident data don't share a clean join key with the financials
table (airline naming inconsistencies across sources), so those tables
were kept as separate facts rather than forced into a single relationship
— a deliberate data-quality decision rather than an oversight.

## 👤 Author -> Ginish Kumar
www.linkedin.com/in/ginish-kumar-544b2a1b4
https://github.com/GinishTech
