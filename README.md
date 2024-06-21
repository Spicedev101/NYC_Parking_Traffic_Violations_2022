# An Analysis of Parking and Traffic Violations in New York City 2022

## Introduction

New York City (NYC) is one of the most traffic-congested cities in the world. Consequently, NYC motorists frequently encounter parking and traffic violation issues. This project aims to explore parking and traffic violation data from NYC for the year 2022 to inform stakeholders about the extent of the problem and provide insights to help improve the situation.

This project is divided into two parts:
1. **Data Cleaning and Exploration:** Documented in this Jupyter Notebook, involves cleaning and exploring the data using SQL.
2. **Data Visualization:** Using Tableau to visualize the data through charts and an interactive dashboard.

The Tableau visualizations and dashboard can be found by [clicking this link](https://public.tableau.com/views/ParkingandTrafficViolationsinNewYorkCity2022/NYCParkingandTrafficViolationsDashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link).

### Key Points
- **Data Cleaning:** Ensuring the data is accurate and ready for analysis.
- **Exploratory Data Analysis (EDA):** Understanding the distribution, trends, and anomalies in the data.
- **Visualizations:** Creating informative and interactive visual representations of the data to highlight key insights.

By combining SQL for data processing and Tableau for data visualization, we aim to provide a comprehensive overview of parking and traffic violations in NYC, identify trends, and suggest possible areas for improvement.

## Skills Used
- **SQL (MySQL):** For data querying, manipulation, and analysis.
- **Tableau:** For creating interactive and visually appealing charts and dashboards.
- **Data Cleaning:** Preparing the data for analysis.
- **Data Visualization:** Presenting data insights effectively.

## Data

The data used in this project was obtained from NYC OpenData. The data was extracted for the year 2022 from two databases related to parking and Traffic violations in NYC:

1. [Parking Violations Issued - Fiscal Year 2023](https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2023/869v-vr48/about_data)
2. [Open Parking and Camera Violations](https://data.cityofnewyork.us/City-Government/Open-Parking-and-Camera-Violations/nc67-uf89/about_data)

In both cases, the data was filtered to extract records for the year 2022. The primary datasets used in this project are:
- `Open Parking and Camera Violations` (Table: `vio_22_time`)
- `Parking Violations Issued - Fiscal Year 2023` (Table: `parking_violations`)

### Data Overview
- **Data Source:** NYC OpenData
- **Year of Analysis:** 2022

## Conclusion

This comprehensive project utilized SQL for data cleaning, preparation, and exploration, and Tableau for visualization and dashboard creation, to analyze NYC parking and traffic violation data for the year 2022. The analysis revealed the following insights:

- Approximately 16.3 million traffic and parking violations, amounting to $1.12 billion in fines, were issued in NYC in 2022.
- The majority of violations (12.3 million) were for vehicles registered in NY.
- Most violations were issued in the morning, peaking around 8:36 AM, with additional peaks at approximately 11:42 AM and 4:06 PM.
- The most violations occurred on Fridays, while the fewest violations were issued on Sundays and Saturdays.
- The Traffic Department was the agency that issued the most violation fines.
- The percentage of unpaid fines was approximately 38.42% for the year 2022.

The findings of this project provide valuable insights for both NYC city administrators and the general public in understanding the realities of parking and traffic violations in NYC. City administrators can use the results to identify areas for improvement, such as violation hotspots and the effectiveness of issuing agencies. The general public can use the findings to better understand the dynamics of parking and traffic violations in the city.
