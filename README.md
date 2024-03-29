# Energy Consumption Dashboard
## Problem Statement
 Energy Consumption Dashboard offers real-time insights into energy costs and consumption. Geared towards identifying cost reduction opportunities and enhancing efficiency, the dashboard tackles challenges such as data accuracy, performance optimization, and user interaction improvements. With a focus on geographic, temporal, type, and building-specific analytics, goal is to provide a powerful yet user-friendly tool. Continuous development ensures the dashboard evolves to meet the dynamic needs of energy management, fostering a culture of data-driven decision-making and efficiency improvement.

 ## Steps Taken
 1.Data Extraction and Transformation:	Data sourced from an Excel spreadsheet.	Power Query used to load and transform data with the first row as headers. Selected the "Energy Consumption" dataset and unpivoted relevant columns.

2.Key Creation for Rate Table:	Created a rate table with "Year" and "Energy Type."Generated a composite key, "Key," by merging "Year" and "Energy Type" columns.

3.Key Creation for Energy Consumption Table:Created a similar "Key" which is the name of the column in the energy consumption table using "Consumption Type" and "Year" columns.

4.Data Modeling and Relationship Management:Automatic establishment of relationships in the Power BI data model based on matching key columns.Manual setup of a one-to-many relationship between dimension and fact tables using the "Key" column.

5.Dashboard Visualization:Designed an Overview page with key metrics and visualizations.Visuals include cards, a map, bar charts, and donut charts for insights.Interactive elements like slicers allow data filtering and drilling down.

6.Narrative and Summary: Descriptive text boxes provide context and highlight critical findings.

7.Polishing and Final Touches:Refined dashboard with a consistent color scheme and clear labels for readability.Positioned and sized visuals for a balanced layout facilitating user comprehension.


## SnapShorts
## Energy Concumption Dashboard | Overview
![Screenshot 2024-01-10 202554](https://github.com/sakshibadoni21/Energy-Consumption-Dashboard/assets/152711814/a956df26-1334-4b35-ad53-e51dc7862b45)

##  Energy Concumption Dashboard |  Water
![Screenshot 2024-01-12 110503](https://github.com/sakshibadoni21/Energy-Consumption-Dashboard/assets/152711814/cc5e2bd2-1fb1-4b1f-bbca-36687552bf97)

## Energy Concumption Dashboard | Electricity
![Screenshot 2024-01-12 111347](https://github.com/sakshibadoni21/Energy-Consumption-Dashboard/assets/152711814/0c806105-4839-408e-89db-6a9338f98683)

## Energy Concumption Dashboard | Gas
![Screenshot 2024-01-12 122447](https://github.com/sakshibadoni21/Energy-Consumption-Dashboard/assets/152711814/9cdbd616-5767-4596-a04b-b8f3d7336326)

## Key Insights 
## Overview
1.	Total Cost and Consumption Tracking:
•	Total Cost: $15.84M
•	Total Units Consumed: 210M.Effective tracking and aggregation of financial and quantitative energy usage data.
2.	Geographical Cost Analysis:
	"Total Cost by City" map allows for region-specific analysis.	Enhances understanding of cost distribution across different cities.
3.	Detailed Summary Insights:
New York's cost is 20.85% higher than Houston, showcasing comparative analytical capabilities.Quick insights into city-wise variations in energy costs.
4.	Consumption Type Breakdown:
Pie chart and stacked bar chart illustrate energy consumption by type.Tracks changes in consumption patterns over time.
5.	Building-Specific Data:
"Unit Consumed by Building" bar chart drills down into finer details of energy consumption across buildings.

## Water Consumption:
1.	Total Water Consumption:
•	Total Cost: $10.81M
•	Total Units Consumed: 186M .Trend Analysis: "Total Cost by Date and Consumption Type" line graph identifies fluctuations over time. City-Specific Distribution: Doughnut chart visually breaks down water costs by city.
## Electricity Consumption:
1.	Total Electricity Consumption:
•	Total Cost: $2.03M
•	Total Units Consumed: 22M.	Interactivity and Filtering: Dropdown menus for building, city, and date enhance user engagement.Time Series Analysis: "Total Cost by Date and Consumption Type" line chart for trend identification. Geographical Cost Distribution: Horizontal bar chart compares costs across cities.
## Gas Consumption:
1.	Total Gas Consumption:
•	Total Cost: $3.01M
•	Total Units Consumed: 3M.Time Series Analysis: "Total Cost by Date and Consumption Type" line chart highlights trends.Geographical Analysis: "Total Cost by City" bar chart for regional cost comparison. Detailed Data Breakdown: Data table offers granular insights into gas consumption.





## Conclusion

The Energy Consumption Dashboard effectively addresses challenges in tracking, analyzing, and optimizing energy usage. With robust features for geographical, temporal, and building-specific insights, it provides a comprehensive tool for energy managers. Key functionalities include real-time tracking, interactive filtering, detailed summaries, and trend analyses, empowering users to make informed decisions for cost reduction and efficiency improvements.





