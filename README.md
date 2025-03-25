## Energy Data Analysis - Summary
This project analyzes a dataset related to energy consumption and costs across different device types, locations, and user types. The analysis aims to uncover insights on energy utilization trends, cost efficiency, operational status, and other important factors related to energy consumption. The dataset provides information on energy utilization (kWh), cost in USD, location (regions A, B, and C), device types (Solar, Hydro, Wind), user types (Residential, Commercial), and the method of payment (Cash, Mobile, Credit). This provides a comprehensive statistical and visual analysis of energy utilization and cost, which can serve as a basis for making informed decisions in energy management and operational optimization across different regions and user types.

### Key Sections of the Analysis:
#### Data Preparation:

The data is cleaned by selecting relevant variables and changing some columns from character to factor types for better analysis.

The locations are standardized, and summary statistics are calculated for each variable.

#### Energy Utilization Analysis:

Total energy consumption per region is calculated.

The analysis explores how energy consumption varies by device type (Solar, Hydro, Wind) using ANOVA and finds that the device type has no significant effect on energy utilization.

The average energy utilization per day and peak energy utilization per region are calculated.

#### Cost Analysis:

The average cost per device type is calculated.

Correlation between energy consumption and cost for each region is examined, revealing a weak correlation.

The cost per energy unit is compared across regions.

The distribution of costs by user type and payment method is analyzed through bar plots and Chi-square tests, revealing no significant relationship between payment method and region or user type.

#### Operational Status Analysis:

The effect of operational status (e.g., active, inactive, maintenance) on energy consumption and cost is explored using ANOVA, which shows no significant difference.

The proportions of operational statuses across regions are visualized and examined.

#### User Type and Payment Method:

Energy utilization differences between user types (Residential vs. Commercial) are analyzed, showing no significant differences.

The most common method of payment across regions and user types is identified, with visualizations of payment methods by region and user type.

The effect of payment method on overall cost is assessed, showing no significant effect.

#### Time Series and Seasonal Patterns:

Trends in energy utilization and cost over time (daily and monthly) are analyzed. This includes identifying months and days with the highest and lowest energy utilization and costs.

Line plots are created to visualize monthly and daily trends in energy utilization and cost.

#### Location-Based Insights:

A detailed analysis of energy utilization and cost differences across regions is provided, showing summary statistics for each location, including average, median, and total costs and utilization.

Boxplots are used to visualize the differences in energy utilization and cost between regions.

#### Device Type Performance:

The device type with the highest energy utilization and the most cost-effective device type is identified.

The energy utilization efficiency for each device type (energy per cost) is calculated.

#### Outliers and Anomalies:

Outliers in energy utilization and cost are detected using boxplots and the Interquartile Range (IQR) method.

Anomalies are flagged for further investigation to ensure data quality.

### Conclusions:
Operational Status and device type did not significantly affect energy utilization or cost, based on the analysis performed.

There was no significant correlation between energy utilization and cost across locations.

The energy utilization and cost trends show seasonal variations, with specific months and days experiencing peaks in both metrics.

Outliers in energy utilization and cost were detected and flagged for further examination.

