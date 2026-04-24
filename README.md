# Energy Intelligence Dashboard  
### Analyzing U.S. energy production, consumption, trade, and energy mix in Power BI

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Analytics](https://img.shields.io/badge/Focus-Advanced%20Analytics-darkgreen)
![Data Modeling](https://img.shields.io/badge/Focus-Data%20Modeling-blue)
![Business Intelligence](https://img.shields.io/badge/Type-Business%20Intelligence-5A9)
![AI Assisted](https://img.shields.io/badge/AI-Assisted%20Development-8A2BE2)

> Designed for both technical and non-technical audiences, delivering a clear understanding without requiring a data background.
---

## Overview

This project analyzes U.S. energy production, consumption, imports, exports, and energy mix across both long-term and monthly time horizons.

The goal was to take a complex dataset and structure it into a dashboard that quickly shows where the energy system stands and how it is evolving over time.

---

## Who This Project Is For

- Energy analysts evaluating production, consumption, and trade dynamics  
- Business intelligence professionals focused on data modeling and reporting  
- Leaders and strategists interested in energy trends, policy implications, and risk exposure  
- Anyone seeking a clear, data-driven view of U.S. energy systems

---

## Key Findings at a Glance

- Energy demand shifts noticeably during major economic and social disruptions  
- Long-term demand growth has plateaued, indicating possible efficiency gains  
- Renewable growth is occurring but remains concentrated in biomass  
- Residential demand introduces significant seasonal volatility  
- The U.S. has transitioned from a net energy importer to a net exporter  

---

## Dashboard Overview

### Energy Position Overview

![US Energy Position](Images/Dashboard/US%20Energy%20Position.png)

**Key Elements:**
- Total production vs consumption alignment  
- Net supply position and variance  
- Energy mix distribution and sector consumption  

**Page Summary:**
Provides a view of how energy supply aligns with demand, helping identify imbalances, trends, and shifts in overall system position. 

---

## Energy Supply & Trade Position

![Energy Supply & Trade Position](Images/Dashboard/Energy%20Supply%20&%20Trade%20Position.png)

**Key Elements:**
- Long-term production growth by source  
- Relative contribution of energy sources  
- Trade dynamics (imports vs exports)  

**Page Summary:**
Highlights how energy is produced and how trade impacts total supply, helping identify dependency risks and shifts toward energy long-term sustainability and independence.

---

## Energy Demand by Sector

![Energy Demand by Sector](Images/Dashboard/Demand%20Analysis%20by%20Sector.png)

**Key Elements:**
- Sector-level consumption trends  
- Seasonal fluctuations in demand  
- Year-over-year consumption changes  

**Page Summary:**
Shows how energy demand varies across sectors and over time, with clear seasonal patterns that impact planning and resource allocation.

---

## Supply-Demand Balance & System Integrity

![Supply-Demand Balance & System Integrity](Images/Dashboard/Supply-Demand%20Balance%20&%20System%20Integrity.png)

**Key Elements:**
- Net supply vs consumption alignment  
- Variance and reconciliation across components  
- Import/export contribution to balancing supply  

**Page Summary:**
Explains how total supply meets demand and identifies where imbalances occur, providing transparency into how the system stays aligned. 

---

## Operational Trends & Short-Term Dynamics

![Operational Trends & Short-Term Dynamics](Images/Dashboard/Operation%20Trends%20&%20Short-Term%20Dynamics.png)

**Key Elements:**
- Monthly production and consumption trends since 1973  
- Short-term fluctuations in energy demand and supply  
- Rolling 12-month production vs Consumption to smooth volatility  
- Latest monthly KPIs (Key Performance Indicators) for real-time system position  

**Page Summary:**
Reveals short-term fluctuations and seasonal demand spikes, helping identify periods of operational stress and the need for responsive supply planning.

---

## Data Model

![Data Model](Images/Dashboard/Data%20Model.png)

A star schema model was implemented to support scalability and performance throughout the report.

- Fact Tables: Production, Consumption, Trade  
- Dimensions: Date, Energy Source, Energy Category  

This structure ensures clear relationships, consistent filtering, accurate aggregation, and flexibility across time granularities.

---

## Key Metrics

- Total Production  
- Total Consumption  
- Net Imports  
- Energy Mix (%)  
- Source Contribution

Measures were designed to remain accurate across both annual and monthly datasets.

Detailed DAX logic is available upon request.

---

## Key Insights

### Macroeconomic Sensitivity

![Insight 1+2](Images/Insights/Insight%201+2.png)

Energy demand declines align with major events:
- 1979–1983 energy crisis  
- 2007–2009 recession  
- 2020 COVID-19 disruption

Energy demand is highly responsive to external events, making it vulnerable to sudden declines during economic disruptions. Organizations must incorporate these risks into forecasting and planning, as demand decline can impact revenue, operations, and resource allocation. 

### Efficiency-Driven Plateau

Post-2009, energy consumption stabilizes despite continued economic growth, indicating improvements in energy efficiency. This marks a structural shift where economic growth no longer directly drives demand. Energy producers must pivot toward efficiency and optimization rather than volume expansion, while consumer-facing companies face increasing pressure to improve product efficiency as energy costs become a competitive factor. 

---

### Renewable Composition Reality

![Insight 3](Images/Insights/Insight%203.png)

While renewable energy is expanding, it remains heavily concentrated in biomass rather than more scalable sources such as solar and wind. This indicates that the transition away from fossil fuels is still in its early stages, with continued reliance on limited and less sustainable energy sources. As demand for long-term energy stability increases, this creates both risk and opportunity — risk through overreliance on a single renewable source, and opportunity for significant expansion in solar and wind, where future investment and innovation are likely to accelerate. 

---

### Seasonal Demand Volatility

![Insight 4](Images/Insights/Insight%204.png)

Seasonal demand spikes driven by temperature extremes and cultural celebration create predictable periods of stress on energy systems. This allows organizations to plan ahead by identifying potential failure points, allocating resources more effectively, and improving response times during high-demand periods. 

- **Operations & Reliability:** Anticipate system stress, position personnel strategically, and reduce downtime during peak usage  

- **Cost Management & Pricing:** Implement time-based pricing or incentives to spread demand and reduce peak load pressure  

- **Product Strategy:** Invest in energy-efficient technologies that help customers reduce consumption during high-cost periods  

- **Sales & Marketing:** Time promotions and pricing plans around peak usage cycles to drive demand and improve margins 

---

### Structural Trade Shift

![Insight 5](Images/Insights/Insight%205.png)

This shift changes the U.S. energy system from supply-dependent to supply-driven, reducing reliance on external sources while opening the door to greater global market participation. It creates new opportunities across multiple parts of the value chain, from production to infrastructure and investment. 

- **Energy Producers:** Export capability enables access to global markets, creating new revenue streams and strengthening long-term competitive positioning  

- **Utilities & Grid Operators:** Greater domestic supply stability improves planning accuracy and reduces disruption risk 

- **Logistics & Infrastructure:** Increased production and export volume drives demand for transportation, storage, and distribution, creating expansion opportunities  

- **Investment & Finance:** The shift introduces opportunities to invest in energy production, infrastructure, and global market participation, supporting portfolio growth and diversification

---

## AI Collaboration

AI tools were used throughout this project to accelerate development and enhance analytical quality.

- Assisted with DAX measure development and optimization  
- Supported data modeling decisions and validation  
- Helped structure dashboards for clarity and usability  
- Used to test and validate insights against the underlying data    

All outputs were reviewed, validated against source data, and refined as needed to ensure accuracy and business relevance.

The analytical framing, data sourcing, and final design decisions were independently developed.

---

## Final Note

This project challenged me to move beyond building visuals and focus on how the analysis would support real decisions.

Rather than simply presenting data, I focused on structuring it in a way that supports clear, informed actions.
