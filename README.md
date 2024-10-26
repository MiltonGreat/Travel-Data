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
      
Strong relationships: 

- Accommodation cost and Transportation cost (0.787): Travelers who spend more on accommodation also tend to spend more on transportation.
- Trip ID and Transportation cost (0.448): As trips are numbered, there is a moderate positive correlation with transportation costs, which could reflect increasing travel costs over time.

Weak or insignificant correlations:

- Duration and travel costs (both accommodation and transportation) are not strongly correlated, meaning that the length of the trip does not directly influence these costs significantly.
- Traveler age shows very weak correlations with other variables, indicating it does not play a major role in influencing trip duration or costs.

#### 7.  Source

https://www.kaggle.com/datasets/rkiattisak/traveler-trip-data
