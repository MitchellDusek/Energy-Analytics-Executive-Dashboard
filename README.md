Energy Intelligence Dashboard 

End-to-End Data Modeling, Analytics, and AI-Assisted Insight Generation 

Overview 

This project delivers a fully structured energy intelligence platform designed to analyze production, consumption, imports, exports, and energy mix across both long-term and monthly time horizons. 

It demonstrates the ability to transform complex, multi-granularity datasets into a scalable analytical model and deliver executive-level insights that support strategic decision-making. 

Executive Summary 

Energy demand is highly sensitive to macroeconomic and societal disruptions  

Long-term consumption growth has plateaued, indicating possible efficiency gains  

Renewable growth is occurring but remains concentrated in biomass  

Residential consumption introduces significant seasonal volatility  

The U.S. has transitioned from a net energy importer to a net exporter 

 

Executive Dashboard 

Executive Overview — Current Energy Position 

![US Energy Position](Images/Dashboard/US Energy Position.png](https://github.com/MitchellDusek/Energy-Analytics-Executive-Dashboard/blob/main/Images/Dashboard/US%20Energy%20Position.png)

What this shows: 

Total production vs consumption alignment  

Net supply position and variance  

Energy mix distribution and sector consumption 

Executive takeaway: This page provides an immediate understanding of whether the system is balanced, where demand is concentrated, and how supply is structured. 

Production & Supply — Long-Term Structural Trends 

What this shows: 

Long-term production growth by source  

Relative contribution of energy sources  

Trade dynamics (imports vs exports) 

Executive takeaway: Energy production has evolved significantly, with natural gas emerging as the dominant source. Trade dynamics show a transition toward energy independence. 

Consumption by Sector — Behavioral & Seasonal Patterns 

What this shows: 

Sector-level consumption trends  

Seasonal fluctuations in demand  

Year-over-year consumption changes 

Executive takeaway: Residential demand introduces predictable but significant seasonal volatility, while industrial and transportation sectors remain more stable drivers of baseline consumption. 

Supply Balance & Reconciliation — System Integrity 

What this shows: 

Net supply vs consumption alignment  

Variance and reconciliation across components  

Import/export contribution to balancing supply 

Executive takeaway: The system remains tightly balanced overall, with recent years showing a shift toward net export positioning — a structural change in energy independence. 

Monthly Detail (1973+) — Operational Trends & Rolling Stability 

What this shows: 

Monthly production and consumption trends since 1973 

Short-term fluctuations in energy demand and supply  

Rolling 12-month production vs 12-month consumption to smooth volatility 

Latest monthly KPIs for real-time system position 

Executive takeaway: While long-term trends suggest stability, monthly data reveals meaningful short-term variability. The rolling 12-month view highlights underlying stability while exposing periods where production and consumption diverge, signaling potential operational stress. 

Data Model 

A star schema model was implemented to ensure scalability and performance. 

Fact Tables: Production, Consumption, Trade  

Dimensions: Date, Energy Source, Energy Category, Sector 

This structure ensures consistent filtering, accurate aggregation, and flexibility across time granularities. 

Key Metrics (DAX) 

Total Production  

Total Consumption  

Net Imports  

Energy Mix (%)  

Source Contribution 

Measures were designed to remain accurate across both annual and monthly datasets. 

Key Insights 

Macroeconomic Sensitivity 

 

Energy demand declines align with major events: 

1979–1983 energy crisis  

2007–2009 recession  

2020 COVID-19 disruption 

Efficiency-Driven Plateau 

Post-2009, energy consumption stabilizes despite continued economic growth, indicating possible improvements in energy efficiency. 

Renewable Composition Reality 

 

Renewable growth is driven primarily by biomass, not solar or wind, highlighting a gap between perception and actual contribution. 

Seasonal Demand Volatility 

 

Residential consumption spikes significantly during summer and winter, creating predictable operational stress periods. 

Structural Trade Shift 

 

The U.S. transitioned from a net importer to a net exporter around 2019, driven by increased domestic production. 

AI Collaboration 

AI was used to accelerate development across: 

Data modeling design  

DAX optimization  

Dashboard structuring  

Insight refinement 

All outputs were validated and refined to ensure accuracy and business relevance. 

Tools & Technologies 

Power BI  

DAX  

Data Modeling (Star Schema)  

Excel  

AI-assisted development 

Final Note 

This project demonstrates the ability to move beyond reporting and build a structured decision-support system. 

The focus is not just on what the data shows — but on what decisions it enables. 

 
