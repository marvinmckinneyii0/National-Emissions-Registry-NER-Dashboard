📊 United States Emissions Breakdown (2023) 
Data Source: EPA (Environmental Protection Agency)
Tools: Databricks SQL, AI/BI Dashboards

Executive Summary
This dashboard provides a granular look at emission distribution across the US. Key insights include:Concentrated Impact: The top 10 states account for 51% of all US emissions.County Leaders: High-density regions like Maricopa County,
AZ and Harris County, TX represent the highest localized outputs.Population Correlation: Analysis of $Emissions\_per\_person$ vs. Population density to identify efficiency trends.

🛠️ Tech Stack
Data Orchestration & Analytics
Databricks (Free Edition): Unified analytics platform for data processing and visualization.

Databricks SQL: Used for querying the EPA GHGRP datasets and power-leveling the dashboard widgets.

AI/BI Dashboards (Lakeview): The visualization layer used to build the geospatial maps and interactive charts.

Languages & Engines
SQL: Primary language for data transformation and aggregation.

Spark SQL Engine: High-performance distributed computing for handling large-scale emissions data.

Data & Mapping
EPA Greenhouse Gas Reporting Program (GHGRP): Source of the 2023 emissions data.

Mapbox / OpenStreetMap: The underlying engine powering the "Emissions Per Location" point map.

Version Control
GitHub: Repository hosting for dashboard definitions and SQL source code.

Databricks Git Folders: For seamless synchronization between the workspace and this repository.


https://dbc-903a52ea-05d7.cloud.databricks.com/dashboardsv3/01f116fa4a931872a6b1107125e69dd9/published?o=7474644284422702
