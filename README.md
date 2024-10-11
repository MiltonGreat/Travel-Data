# Travel-Data

### Summary and Recommendations

#### 1. Overview

This project analyzes a dataset related to travel, including details such as trip duration, cost, and traveler demographics. The goal of the project is to perform Exploratory Data Analysis (EDA) to uncover travel patterns, trends over time, and correlations between different trip metrics. Visualizations such as line plots, scatter plots, and geographic maps are used to present key insights.

#### 2. Data

The dataset contains information on individual trips taken by travelers, with columns including:

  - Destination: The travel destination (city or country).
  - Traveler age: The age of the traveler.
  - Start and End Date: The start and end dates of the trip.
  - Duration (days): The duration of the trip in days.
  - Accommodation cost: The total cost of accommodation for the trip.
  - Transportation cost: The total cost of transportation for the trip.

#### 3. Data Analysis Steps

1. Data Loading and Inspection
2. Data Cleaning
3. Feature Engineering
  - Duration calculation
  - Country extraction
4. Data Visualization
  - Line plot of monthly trips over time
  - Scatter plots for cost vs. duration
  - Choropleth map for country visits
  - Bar plots for average costs by country
  - Outlier detection in cost columns
  
#### 4. Data Cleaning 

- Missing values in categorical columns (e.g., Destination, Transportation type) were filled with the most frequent value.
- Missing values in numerical columns (e.g., Duration, Traveler age) were filled with the mean.
- Currency symbols in the cost columns were removed, and the values were converted to numeric types for analysis.
- Standardization of categorical columns was performed to ensure consistent values (e.g., "Plane" and "Airplane" were both replaced by "Flight").

#### 5. Data Visualization

- Line Plot of monthly trips over time.
- Scatter Plots showing the relationship between trip duration and costs (accommodation and transportation).
- Choropleth Map showing the number of visits by country.
- Bar Plots comparing average accommodation and transportation costs by country.
- Boxplots for outlier detection in accommodation and transportation costs.

#### 6. Key Findings
      
Popular Travel Destinations: The most visited destinations include major global cities such as New York, London, and Tokyo, reflecting the popularity of large urban centers among travelers.

Seasonal Travel Patterns: Travel trends show a seasonal pattern, with peaks in the number of trips during the summer and around winter holidays, suggesting that travelers are more likely to take trips during traditional vacation periods.

Cost and Duration Relationship: Longer trips tend to incur higher accommodation and transportation costs, but there is considerable variability based on the destination and travel style.

Country-Level Costs: Accommodation and transportation costs vary widely across different countries, with destinations like New York and Tokyo having higher average accommodation costs compared to other locations.

Outliers in Cost: Outliers in accommodation and transportation costs suggest that a few trips involved unusually high or low spending, potentially representing luxury travel or budget trips.

#### 7.  Source

https://www.kaggle.com/datasets/rkiattisak/traveler-trip-data
