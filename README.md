# **ECONOMIC GROWTH - DATA VISUALIZATION AND ANALYSIS
# **Overview
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

# **SUMMARYY STATISTICS
![image](https://github.com/user-attachments/assets/082f3ab9-382d-4075-b804-c1cd72dde053)

This data set contains 63 observations and four different variables. GDP Growth averages at about 3.03%, which is higher than the median, indicating the presence of outliers. This is typically reflected by a slight positive skew. It also has moderate variation shown by a standard deviation of 2.11, and has a minimum value of  -2.58%, indicating a recession and a maximum of 7.24%, indicating an expansion. Net Migration has a mean of positive 2.47%, meaning that there are more people entering the country, since it is calculated by the number of immigrants minus the number of emigrants. It has a negative median, suggesting that there is a decrease in net migration compared to prior periods. Because we used percentage change as our unit of measurement, we see a high standard deviation. Unemployment Rate is mostly stable with a mean of 5.92%, which is close to the median of 5.62%. It also has a narrow range (3.49% to 9.71%) and low variability (SD: 1.63). Lastly, Inflation has an average of 3.81%, close to the median, with moderate variability (SD: 2.77), spanning deflationary periods (-0.36%) to high inflation (13.55%). 


# ** MAIN DATA VISUALIZATIONS

   
# **TECHNOLOGY USED
Programming Language: R. The code is organized and presented in an R Markdown (RMD) file, with executable chunks for clarity and reproducibility.

