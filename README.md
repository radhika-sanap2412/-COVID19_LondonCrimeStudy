
# London Crime Analysis: Impact of COVID-19
## Introduction
The COVID-19 pandemic brought unprecedented changes to everyday life, including shifts in crime patterns. This analysis examines how various types of crimes were affected by the pandemic in London, with a particular focus on periods of lockdown and other restrictive measures. The findings aim to provide insights into the social consequences of the pandemic and inform future policy decisions.

## Data Sources
London Crime Data: Monthly crime statistics across London boroughs https://data.london.gov.uk/dataset/mps-monthly-crime-dahboard-data.
COVID-19 Data: Information on COVID-19 cases, lockdown periods, and government responses.
Demographic Data: Population data for London boroughs, used to normalize crime rates.
## Methodology
Time Series Analysis
The core of this study involves a detailed time series analysis of crime data across London. The following steps outline the approach:

Data Collection and Preparation:

Monthly crime data was collected for various categories such as burglary, theft, violent crime, and domestic violence.
The data was segmented into pre-pandemic, during-pandemic, and post-pandemic periods to allow for a clear comparison across different phases of the COVID-19 crisis.
Trend Analysis:

Seasonal Decomposition: The crime data was decomposed into seasonal, trend, and residual components to identify underlying patterns. This helped in isolating the effect of seasonality from the actual trends caused by the pandemic.
Moving Averages: To smooth out short-term fluctuations and highlight longer-term trends, moving averages were applied to the crime data. This was particularly useful in understanding the overall direction of crime rates before, during, and after the pandemic.
Lockdown Impact Analysis:

The analysis focused on periods corresponding to the UK's lockdowns and social restrictions. The impact of these measures on crime rates was analyzed using interrupted time series analysis (ITSA), which allowed for the examination of immediate changes in crime following the imposition or lifting of lockdowns.
Comparison of Lockdown Phases: Different phases of lockdown (e.g., full lockdown vs. partial restrictions) were compared to assess their differential impact on various types of crimes.
Statistical Testing:

Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF): These were used to assess the presence of autocorrelation in the crime data, which informed the selection of appropriate time series models.
ARIMA Modeling: For predictive analysis, ARIMA (AutoRegressive Integrated Moving Average) models were fitted to the crime data. This helped in understanding the expected crime trends in the absence of the pandemic, providing a baseline against which the actual data could be compared.
Visualization:

Various plots were generated to visually explore the trends in crime data over time. These include line charts for overall crime rates, bar charts for comparing pre- and post-pandemic periods, and heatmaps to show geographic variations in crime trends across London boroughs.
Geospatial Analysis
Mapping Crime Data: Crime rates were mapped to visualize the geographic impact of the pandemic. This highlighted areas with significant increases or decreases in crime during lockdowns.
Spatial Correlation: Moran’s I and Local Indicators of Spatial Association (LISA) were used to assess the spatial correlation of crime rates across London, revealing clusters of high and low crime rates during different phases of the pandemic.
Correlation Analysis
Correlation with COVID-19 Cases: The correlation between the number of COVID-19 cases and changes in crime rates was explored, providing insights into how the pandemic's progression influenced criminal activity.
Socioeconomic Factors: The analysis also considered correlations with socioeconomic data, such as population density and deprivation indices, to understand the broader context of crime trends during the pandemic.
## Key Findings
Decrease in Property Crimes: Significant reductions in crimes like burglary and theft during lockdown periods, with the most notable drops occurring during the strictest lockdown phases.
Increase in Domestic Violence: A noticeable rise in domestic violence incidents, particularly during the initial lockdown, correlating with stay-at-home orders.
Geographic Variability: Crime patterns varied widely between different areas, with some boroughs experiencing greater changes than others.
## Conclusion
The COVID-19 pandemic had a marked impact on crime rates in London, with both positive and negative changes observed across different types of crime. The time series analysis revealed clear trends, including a general reduction in property crimes and an increase in domestic-related incidents. These findings highlight the need for targeted interventions and policies to address the varying effects of the pandemic on different communities.
