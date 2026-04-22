# Energy Intelligence Dashboard  
### End-to-End Data Modeling, Analytics, and AI-Assisted Insight Generation

> Designed for both technical and non-technical audiences, delivering clear, executive-level insights without requiring a data background.
---

## Overview

This project delivers a fully structured energy intelligence platform designed to analyze production, consumption, imports, exports, and energy mix across both long-term and monthly time horizons.

It demonstrates the ability to transform complex datasets into a scalable analytical framework and deliver decision-ready insights for strategic and operational use.

---

## Who This Project Is For

- Energy analysts evaluating production, consumption, and trade dynamics  
- Business intelligence professionals focused on data modeling and reporting  
- Decision-makers and strategists interested in energy trends, policy implications, and risk exposure  
- Anyone seeking a clear, data-driven view of U.S. energy systems

---

## Executive Summary

- Energy demand is highly sensitive to macroeconomic and societal disruptions  
- Long-term demand growth has plateaued, indicating possible efficiency gains  
- Renewable growth is occurring but remains concentrated in biomass  
- Residential demand introduces significant seasonal volatility  
- The U.S. has transitioned from a net energy importer to a net exporter  

---

## Dashboard Overview

### US Energy Position

![US Energy Position](Images/Dashboard/US%20Energy%20Position.png)

**What this shows:**
- Total production vs consumption alignment  
- Net supply position and variance  
- Energy mix distribution and sector consumption  

**Executive takeaway:**
This page provides an immediate understanding of whether the system is balanced, where demand is concentrated, and how supply is structured.

---

## Energy Supply & Trade Positions

![Energy Supply & Trade Position](Images/Dashboard/Energy%20Supply%20&%20Trade%20Position.png)

**What this shows:**
- Long-term production growth by source  
- Relative contribution of energy sources  
- Trade dynamics (imports vs exports)  

**Executive takeaway:**
Energy production has evolved significantly, with natural gas emerging as the dominant source. Trade dynamics show a transition toward energy independence.

---

## Demand Analysis by Sector

![Demand Analysis by Sector](Images/Dashboard/Demand%20Analysis%20by%20Sector.png)

**What this shows:**
- Sector-level consumption trends  
- Seasonal fluctuations in demand  
- Year-over-year consumption changes  

**Executive takeaway:**
Residential demand introduces predictable but significant seasonal volatility, while industrial and transportation sectors remain more stable drivers of baseline consumption.

---

## Supply-Demand Balance & System Integrity

![Supply-Demand Balance & System Integrity](Images/Dashboard/Supply-Demand%20Balance%20&%20System%20Integrity.png)

**What this shows:**
- Net supply vs consumption alignment  
- Variance and reconciliation across components  
- Import/export contribution to balancing supply  

**Executive takeaway:**
The system remains tightly balanced overall, with recent years showing a shift toward net export positioning — a structural change in energy independence.

---

## Operation Trends & Short-Term Dynamics

![Operation Trends & Short-Term Dynamics](Images/Dashboard/Operation%20Trends%20&%20Short-Term%20Dynamics.png)

**What this shows:**
- Monthly production and consumption trends since 1973  
- Short-term fluctuations in energy demand and supply  
- Rolling 12-month production vs Consumption to smooth volatility  
- Latest monthly KPIs for real-time system position  

**Executive takeaway:**
While long-term trends suggest stability, monthly data reveals meaningful short-term variability. The rolling 12-month view highlights underlying stability while exposing periods where production and consumption diverge, signaling potential operational stress.

---

## Data Model

![Data Model](Images/Dashboard/Data%20Model.png)

A star schema model was implemented to ensure scalability and performance.

- Fact Tables: Production, Consumption, Trade  
- Dimensions: Date, Energy Source, Energy Category  

This structure ensures consistent filtering, accurate aggregation, and flexibility across time granularities.

---

## Key Metrics (DAX - PowerBI formula language)

- Total Production  
- Total Consumption  
- Net Imports  
- Energy Mix (%)  
- Source Contribution

![Measures Table](Images/Dashboard/Measures%20Table.png)

For a full view of all DAX you can click [HERE](PowerBi/Energy%20Sector%20Dashboard.pbix) to view the PowerBI Measures Table

Measures were designed to remain accurate across both annual and monthly datasets.

---

## Key Insights

### Macroeconomic Sensitivity

![Insight 1+2](Images/Insights/Insight%201+2.png)

Energy demand declines align with major events:
- 1979–1983 energy crisis  
- 2007–2009 recession  
- 2020 COVID-19 disruption  

---

### Efficiency-Driven Plateau
Post-2009, energy consumption stabilizes despite continued economic growth, indicating improvements in energy efficiency.

---

### Renewable Composition Reality

![Insight 1+2](Images/Insights/Insight%203.png)

Renewable growth is driven primarily by biomass, not solar or wind, highlighting a gap between perception and actual contribution.

---

### Seasonal Demand Volatility

![Insight 1+2](Images/Insights/Insight%204.png)

Residential consumption spikes significantly during summer and winter, creating predictable operational stress periods.

---

### Structural Trade Shift

![Insight 1+2](Images/Insights/Insight%205.png)

The U.S. transitioned from a net importer to a net exporter around 2019, driven by increased domestic production.

---

## AI Collaboration

AI was used to accelerate development across:

- Data modeling design  
- DAX optimization  
- Dashboard structuring  
- Insight refinement  

All outputs were validated and refined to ensure accuracy and business relevance.

---

## Tools & Technologies

- Power BI  
- DAX  
- Data Modeling
- Excel  
- AI-assisted development  

---

## Final Note

This project demonstrates the ability to move beyond reporting and build a structured decision-support system.

The focus is not just on what the data shows — but on what decisions it enables.
