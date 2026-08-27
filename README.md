# Logistic-company-analysis

description


## Executive summary
<p align="center">
<img src="Screenshots/01_Executive_summary.png" width="900">

## Key findings
### Financial Performance
- Revenue remained stable at approximately $88M annually.
- Total operating costs decreased from $36M in 2022 to $32M in 2024.
- Net revenue increased from $52M to $56M over the period.
 
### Operational Performance
- More than 85,000 trips were completed.
- Fleet efficiency remained stable around 6.5 MPG.
- Safety incidents remained below 60 events per year.
 
### Customer Analysis
- The top five customers generated a significant share of total revenue.
 
### Seasonality
- Revenue shows recurring seasonal patterns.
- February consistently appears below average while summer months show stronger performance.

## Customer's analysis
<p align="center">
<img src="Screenshots/02_Customer_analysis.png" width="900">

## Key findings
### Sector Performance
Automotive generated the highest revenue over the analyzed period, exceeding $55M.

### Customer Mix
The customer base is well diversified across six major sectors, with no sector representing an excessive concentration risk.

### Growth
Consumer Goods showed the strongest recent growth, while Automotive experienced a slight contraction during the last year.

### Operational Trends
Trip volumes remained stable across the three-year period, suggesting consistent demand.

## Route Profitability
<p align="center">
<img src="Screenshots/03_route_profitability.png" width="900">

## Key findings
### Route Profitability
 - The most profitable transportation lanes achieved profit margins close to 70%, indicating a highly efficient pricing and cost structure on selected routes.
 - Profitability among the top-performing routes is relatively homogeneous, suggesting that the company's route network is optimized and does not rely on a single exceptionally profitable lane.
 - Several routes generate similar profit margins despite different geographic destinations, highlighting opportunities to replicate successful operational practices across the network.

### Geographic Performance
 - Oregon, California, Washington, Texas and Pennsylvania represent the largest contributors to net revenue, making them strategically important markets for the business.
 - High-revenue states do not always coincide with the states exhibiting the highest profit margins, confirming that revenue alone is not a sufficient indicator of route performance.
 - States such as Nevada, Oregon and North Carolina show some of the strongest margins, suggesting favorable operating costs and/or pricing conditions.

### Hub Efficiency
 - Kansas City is the most frequently used origin hub, indicating its central role within the transportation network.
 - Although not the busiest location, Columbus ranks among the hubs with the strongest profitability performance, demonstrating that operational efficiency can outweigh pure shipment volume.
 - The comparison between hub frequency and hub profitability highlights potential opportunities to redirect volumes toward more profitable network nodes.

### Business Recommendations
 - Increase commercial focus on high-margin routes to maximize profitability while maintaining service quality.
Investigate the operational practices of top-performing hubs and replicate them across lower-margin locations.
 - Evaluate whether additional capacity should be allocated to states and routes combining both high revenue contribution and strong profit margins.
 - Monitor route profitability over time to identify changes in fuel costs, demand patterns, or operational efficiency that could affect network performance.

## Safety Metrics
<p align="center">
<img src="Screenshots/04_safety_metrics.png" width="900">

## Key findings
### Safety Performance Overview
 - A total of 170 safety incidents were recorded during the three-year period, generating more than $2.6M in claims and related costs.
 - Despite a slight increase in incident volume in 2024, the average cost per incident decreased compared to 2022, suggesting improved cost control and incident management practices.
 - Injury-related events remained relatively stable, accounting for approximately one fifth of all incidents throughout the analyzed period.
   
### Incident Cost Drivers
 - Equipment Damage represents the most expensive category, generating the highest total financial impact across all incident types.
 - DOT Violations and operational accidents also contribute significantly to overall safety costs, highlighting compliance and operational execution as key risk areas.
 - The gap between total cost and cost per incident indicates that not all incident categories have the same financial severity, emphasizing the need to prioritize prevention efforts based on economic impact rather than event frequency alone.

### Preventability Analysis
 - Approximately 38% of all incidents were classified as preventable, revealing a significant opportunity for targeted risk-reduction initiatives.
 - Equipment-related incidents exhibit the highest overall preventability rate, suggesting that preventive maintenance programs and vehicle inspections could generate measurable safety improvements.
 - Traffic-related events also show elevated preventability levels, indicating that driver training and defensive driving programs may help reduce future occurrences.
 - Weather-related incidents display the lowest preventability rates, confirming that external environmental factors remain a substantial source of unavoidable risk.
 - 
### Geographic Risk Distribution
 - Safety events are concentrated in a limited number of states, indicating that risk exposure is not evenly distributed across the transportation network.
 - States with the highest incident count should be investigated further to determine whether the higher frequency is driven by increased operational volume or by underlying safety issues.
 - Comparing incident frequency with route profitability can help identify locations where strong financial performance may be offset by elevated risk costs.

### Driver Experience Analysis
 - Incidents are distributed across multiple experience levels rather than being concentrated exclusively among newer drivers.
 - The relationship between experience and incident frequency appears non-linear, suggesting that experience alone is not a sufficient predictor of safety performance.
 - Additional driver-level indicators such as miles driven, route complexity, training history, and vehicle assignment should be considered when evaluating safety risk.
   
### Business Recommendations
 - Prioritize preventive actions on equipment-related incidents, which combine high cost impact and high preventability.
 - Strengthen compliance monitoring and driver coaching programs to reduce DOT violations and traffic-related incidents.
 - Implement safety KPIs at driver and route level to identify recurring risk patterns before they generate significant financial losses.
 - Integrate profitability and safety metrics in management reporting to ensure that operational growth does not come at the expense of increased risk exposure.

## Maintenance Analysis
<p align="center">
<img src="Screenshots/05_maintenance_analysis.png" width="900">

## Key findings
### Maintenance Cost Overview
 - The fleet required 2,920 maintenance interventions over the three-year period, generating a total maintenance expenditure exceeding $5.7M.
 - Maintenance spending remained relatively stable across the analyzed years, indicating a mature asset management strategy and consistent maintenance planning.
 - Average intervention cost remained close to $2,000 per repair, suggesting effective control over maintenance expenses despite significant fleet utilization.

### Maintenance Categories
 - Repair, Preventive Maintenance, and Brake-related activities account for the largest share of maintenance spending.
 - Preventive maintenance represents a substantial portion of total expenditures, highlighting a proactive maintenance strategy rather than a reactive "run-to-failure" approach.
 - Inspection-related activities generated significantly lower costs compared to repair-oriented interventions, emphasizing the importance of routine inspections in preventing more expensive failures.

### Fleet Manufacturer Performance
 - Fleet composition is relatively balanced among all major OEMs, reducing operational dependency on a single manufacturer.
 - Revenue generation differs across manufacturers, with some OEMs generating substantially higher revenue despite similar fleet representation.
 - Variations in maintenance costs and labor requirements indicate that asset performance is not uniform across manufacturers and should be considered when planning future fleet acquisitions.

### Equipment Utilization
 - Average odometer readings at maintenance events are remarkably consistent across OEMs, suggesting a standardized maintenance scheduling process throughout the fleet.
 - High utilization levels combined with stable maintenance costs indicate that assets are being used efficiently without generating disproportionate repair expenses.
 - Vehicles with higher revenue contribution should be monitored closely to ensure maintenance capacity remains aligned with operational demand.
### Labor and Downtime Analysis
 - Average labor hours per intervention remained stable at approximately 4 hours, indicating predictable maintenance workloads and repair complexity.
 - Average downtime per intervention remained consistent across the analyzed period, suggesting that workshop operations and maintenance planning are effectively controlled.
 - Minimizing downtime remains a key opportunity because even small reductions can increase fleet availability and improve overall asset utilization.

### Business Recommendations
 - Continue prioritizing preventive maintenance activities, as they help contain long-term repair costs and reduce unexpected equipment failures.
 - Evaluate maintenance performance at the OEM level to identify manufacturers delivering the best balance between revenue generation, maintenance costs, and reliability.
 - Monitor downtime and labor efficiency as leading indicators of future maintenance performance.
 - Incorporate maintenance cost metrics into fleet replacement decisions to ensure that aging assets do not negatively impact profitability.

## Tools Used
### Database
 - PostgreSQL (Neon)

### Analysis
 - SQL
 - CTEs
 - Aggregations
 - Joins

### Visualization
 - Power BI

### Version Control
 - GitHub
