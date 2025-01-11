# **THE INFLUENCE OF NET MIGRATION, UNEMPLOYMENT, AND INFLATION ON ECONOMIC GROWTH
# **OVERVIEW
This project investigates the dynamic interplay between net migration, unemployment rates, and inflation, focusing on their collective impact on economic growth in the United States. Using time-series data spanning from 1961 to 2023, the study examines how these variables influence real GDP trends, providing valuable insights into economic drivers and the implications of policy decisions.

# **DATA USED 
The study leverages time-series data over 63 years (1961–2023) from reputable sources, including the Federal Reserve and the World Bank, to evaluate economic growth and its key determinants. Key datasets include:
1. Net Migration: Derived as the difference between immigration inflows and emigration outflows.
2. Unemployment Rate: Percentage of the labor force actively seeking employment but currently jobless.
3. Inflation: Annual percentage change in the Consumer Price Index (CPI).
4. Real GDP: Percentage change in the total value of goods and services produced annually.

For more details about the dataset:
Unemployment Rate: https://fred.stlouisfed.org/series/UNRATE, annual percent, FRED data
Real GDP: https://fred.stlouisfed.org/graph/?g=1aEiA, percent change from a year ago, FRED data 
Inflation: https://fred.stlouisfed.org/series/FPCPITOTLZGUSA , percent, FRED data
Net Migration: https://data.worldbank.org/indicator/SM.POP.NETM?locations=us , percent change, World Bank

# **SUMMARY STATISTICS
![image](https://github.com/user-attachments/assets/082f3ab9-382d-4075-b804-c1cd72dde053)

# General Information:
   Contains 63 observations across 4 variables.
# GDP Growth:

   Mean: 3.03% (higher than the median, indicating outliers).
   Skew: Slight positive skew.
   Variation: Standard deviation (SD): 2.11.
   Range: Minimum -2.58% (recession) to maximum 7.24% (expansion).
# Net Migration:

   Mean: 2.47% (positive, indicating more immigrants than emigrants).
   Median: Negative, showing a decline compared to earlier periods.
   Variation: High SD due to percentage change measurement.
# Unemployment Rate:

   Mean: 5.92% (close to the median of 5.62%).
   Range: 3.49% to 9.71% (narrow).
   Variation: Low SD of 1.63.
# Inflation:

   Mean: 3.81% (close to the median).
   Variation: Moderate SD of 2.77.
   Range: -0.36% (deflation) to 13.55% (high inflation).

# ** MAIN DATA VISUALIZATIONS

![normalized_data_all_indicators](https://github.com/user-attachments/assets/f4f96528-ab55-45b3-8893-ef883635d005)
The gray areas, in the image above,  represent U.S. recessions. Inflation drops during the 1973-75 and 1980-82 recessions due to oil shocks. GDP growth decreases in recessions, influenced by events like the 2008 housing crisis and COVID-19. Unemployment rises during these periods, as seen in 2020 with pandemic-related job losses. Net migration increases during recessions, possibly due to lower living costs. In 1990, the Immigration Act boosted immigration by allocating visas for special immigrants and investors.
 # For full details about the data visualizations and the interpretation see the research paper
 ![real_gdp_plot_visualization](https://github.com/user-attachments/assets/a7872964-456b-420d-b6ee-4c071929959a)

![inflation_plot_visualization](https://github.com/user-attachments/assets/7fdf00d5-71df-46e8-8678-fc52f54705a5)
![plot_regression_inflation](https://github.com/user-attachments/assets/d1985d16-7f2b-4607-a653-d21fefd33533)
![NET_MIGRATION_REGRESSION](https://github.com/user-attachments/assets/5e5d2bf4-bf69-45f5-a9f5-7a1b54199c0e)
![netmigration_plot_visualization](https://github.com/user-attachments/assets/a7410d3d-9ebf-4480-b02f-f3e36c4c5bb5)
![unrate_plot_visualization](https://github.com/user-attachments/assets/8ece5151-85a1-4426-905f-a01fb2425f00)
![UR_REGRESSION](https://github.com/user-attachments/assets/981d4fc1-0624-4cd5-bf2a-06ebd2ca04a4)
![multi_regression_plot_high_quality](https://github.com/user-attachments/assets/944e5c75-951f-4675-ab0f-69c963d0a781)


# **TECHNOLOGY USED
Programming Language: R. The code is organized and presented in an R Markdown (RMD) file, with executable chunks for clarity and reproducibility.

