# Airfare Price and Passenger Rate Analysis (1997-2023)

## Table of Contents
- [Business Questions](#buisness-questions)
- [Project Overview](#projecy-overview)
- [Summary of Insights](#summary-of-insights)
- [Limitations](#limitations)
- [Recommendations](#Recommendations)


## Business Questions 
- Is airline passenger demand price sensitive at the industry level?
- Do fare increases consistently lead to declines in passenger volume?
- Are major passenger declines more closely aligned with fare changes or macroeconomic disruptions?

## Project Overview
This project analyzes US airline passenger demand and average airfares from 1997 to 2023 to evaluate whether airline demand is price sensitive. The goal was to determine whether fare increases consistently lead to declines in passenger volume or whether macroeconomic disruptions play a larger role in demand fluctuations.

### Data Collection
This data was collected on Kaggle. It can be found here: [Kaggle US Airline Flight Routes and Fares](https://www.kaggle.com/datasets/amitzala/us-airline-flight-routes-and-fares?)

### Dashboard Preview 
Table that shows YOY percent changes in average fare rates and passenger change
![YOY Table](Elements/YOY_Table.png)

Area graph that shows the results 
![area_graphl](Elements/Area_Graph.png)

The full Tableau dashboard can be found [here](https://public.tableau.com/app/profile/karl.r6258/viz/airfare_17721211767540/Dashboard1)

## Summary of Insights
Across the 1997–2023 analysis period, airline passenger demand does not appear consistently sensitive to airfare changes. While certain years show fare increases alongside shifts in passenger volume, the largest demand fluctuations align more closely with macroeconomic disruptions than pricing alone.

### Major Demand Declines and External Shocks
Several of the most significant passenger declines coincide with major external events rather than substantial fare increases.

- 2001 – Passenger volume declined following the September 11 attacks despite relatively moderate fare movement. The contraction appears driven by safety concerns and reduced travel confidence rather than price sensitivity.
- 2008–2009 – During the global financial crisis, passenger demand fell amid economic uncertainty and reduced discretionary spending. Fare changes alone do not fully explain the magnitude of the decline.
- 2020 – The COVID 19 pandemic caused an unprecedented collapse in passenger volume. Although fares declined, the drop in demand far exceeded price adjustments, indicating that travel restrictions and health concerns were the primary drivers.
### Fare Increases with Limited Demand Impact
- In multiple years, fare increases were not followed by significant declines in passenger volume.
- 2022 – Airfares rose sharply amid inflation and higher fuel costs, yet passenger demand rebounded strongly during the post pandemic recovery period. This suggests pent up travel demand outweighed short term price sensitivity.
- Across much of the post 2010 period, gradual fare increases occurred alongside stable or growing passenger demand, further indicating limited aggregate elasticity at the industry level.

### Overall Interpretation
Airline passenger demand is driven more by macroeconomic shocks than by fare changes. At the industry level, demand appears relatively resilient to short term price increases.

## Limitations 
- This analysis uses industry level yearly data, which may hide differences across individual routes or regions.
- Macroeconomic factors such as GDP, unemployment, and fuel prices were not directly included in the model. As a result, external shocks are interpreted based on timing rather than statistical testing.
- Using annual data also smooths short term fluctuations that may show temporary price sensitivity within a given year.
  
## Recommendations  
- Monitor passenger demand behavior during periods of sustained fare increases to determine whether a long term price threshold exists.
- Compare pre and post 2020 demand trends to evaluate whether price sensitivity has shifted following the pandemic.
- Incorporate economic indicators such as fuel prices or unemployment rates in future analysis to better distinguish between pricing effects and macroeconomic impacts.


 
