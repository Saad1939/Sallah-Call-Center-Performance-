# Sallah Call Center Performance Dashboard

## Project Overview

An interactive Power BI dashboard designed to analyze call center performance, monitor operational KPIs, and evaluate agent efficiency across multiple projects and reporting periods.

The project transforms raw monthly CSV files into a consolidated analytical dataset, enabling stakeholders to monitor call handling performance and identify operational trends.

## Business Objectives

* Monitor overall call center performance.
* Analyze handled and total calls.
* Track monthly call volume and identify peak periods.
* Evaluate Average Speed of Answer (ASA) across agents and projects.
* Support data-driven operational decisions through interactive visualizations.

## Tools & Technologies

* **Power BI** — Dashboard development and visualization.
* **Power Query** — Data cleaning, transformation, and consolidation.
* **DAX** — KPI calculations and analytical measures.
* **CSV** — Source data format.

## Data Preparation

The project involved:

* Consolidating three monthly CSV files covering February through April.
* Cleaning and standardizing data using Power Query.
* Creating a Month dimension to support time-based analysis.
* Preparing the dataset for consistent reporting across different projects and agents.

## Key Findings

* Achieved a handled-call ratio of approximately **98.7%** in the analyzed dataset.
* Identified March as the peak month, with approximately **0.88 million calls**.
* Compared Average Speed of Answer (ASA) across agents and projects.
* Developed interactive visualizations to explore call center performance.

*Note: These figures reflect the analyzed dataset and should be validated against the final dashboard before publication.*

## Dashboard Preview

Add your dashboard screenshots to the `Screenshots` folder and display them here.

Example:

`![Dashboard Overview](Screenshots/dashboard_overview.png)`

## Repository Contents

* `Dashboard/` — Power BI project file.
* `Screenshots/` — Dashboard preview images.
* `Documentation/` — Supporting documentation and business insights.
* `README.md` — Project overview and documentation.

## How to Explore the Project

1. Download the `.pbix` file from the repository.
2. Open it using Power BI Desktop.
3. Explore the dashboard pages, KPIs, filters, and visualizations.

## Skills Demonstrated

Power BI | Power Query | DAX | Data Cleaning | Data Modeling | Data Visualization | Business Intelligence | KPI Analysis
## Business Insights

### 1. Overall Call Handling Performance

The call center handled approximately 98.68% of all offered calls, indicating a high overall call-handling ratio during the analyzed period.

### 2. March Experienced a Significant Increase in Call Volume

March recorded 876,199 offered calls, compared with 446,217 in February. This represented an increase of approximately 96.4% in incoming call volume.

### 3. March Had the Lowest Service Level

The service level declined from 94.68% in February to 87.06% in March before recovering to 95.53% in April.

This decline indicates that a smaller proportion of incoming calls were answered within the defined threshold during March.

### 4. Increased Abandonment Rate in March

The abandonment rate increased from 0.48% in February to 2.15% in March, then decreased to 0.50% in April.

The March result highlights an area for further investigation into waiting times, staffing capacity, and daily call demand.

### 5. Average Speed of Answer

Average ASA increased from 5.78 in February to 14.43 in March, before declining to 7.05 in April.

This pattern suggests a deterioration in answer speed during March, followed by a recovery in April. The unit of measurement and unusually high individual values should be validated before operational conclusions are finalized.

### 6. Project Performance Comparison

Project C recorded the highest handling ratio (99.14%), the highest service level (95.16%), and the lowest abandonment rate (0.86%) among the three projects.

Project B recorded the lowest handling ratio (98.34%) and service level (90.33%), as well as the highest abandonment rate (1.66%).

Differences in workload and call volume should be considered when interpreting these comparisons.

## Business Recommendations

* Investigate the operational factors behind March's increased call volume and lower service level.
* Review staffing levels and workload distribution during peak periods.
* Monitor ASA and abandonment rate together to identify potential service bottlenecks.
* Compare agent performance using average ASA and call-handling metrics rather than the sum of ASA.
* Validate unusually high ASA observations and confirm the service-level calculation before making operational decisions.

## Author

**Saad Ezzat Shalaby**

GitHub: [Saad1939](https://github.com/Saad1939)
