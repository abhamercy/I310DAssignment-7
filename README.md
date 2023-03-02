# I310DAssignment-7
wiki api link: https://pypi.org/project/Wikipedia-API/ 

Introduction:  In this data analysis project, I explored poverty rates according to two different indicators: Poverty rates published by the World Bank and Poverty rates published by the CIA. We will use data from 142 countries collected by these organizations to calculate basic descriptive statistics, create visualizations, and examine the relationship between poverty rates according to the two indicators. My goal for this analysis was to gain a deeper understanding of the distribution and variability of poverty rates across different countries and regions, and to shed light on the challenges and complexities of measuring and addressing poverty around the world.

Data Description: For this analysis, I used a dataset on poverty rates across countries. It includes two indicators of poverty: Poverty(WorldBank) and Poverty(CIA). Each indicator represents the percentage of a country's population living below the poverty line, as defined by either the World Bank or the Central Intelligence Agency (CIA).

The dataset contains data on 142 countries. For each country, the poverty rate is reported for both indicators. The dataset also includes the name of the country and its region.

Descriptive Statistics: I observed that the mean poverty rate for the CIA indicator is slightly higher than the World Bank indicator. The standard deviation is also quite high, indicating a large variability in poverty rates across countries. The minimum poverty rate for both indicators is 0.2%, while the maximum poverty rate is 85.7%.

Data Visualization: For the analysis, we created three visualizations using Python's Matplotlib library.

I first created two histograms to visualize the distribution of poverty rates for both indicators. The x-axis is the poverty rate, and the y-axis is the number of countries with that poverty rate. We used 20 bins to create a smooth distribution.

Then I created a scatter plot to visualize the relationship between poverty rates according to the World Bank and the CIA. The x-axis represents the poverty rate according to the World Bank, and the y-axis represents the poverty rate according to the CIA. Each data point represents a country, and the color represents the region.

Insights from the visualizations:
From the histograms, I can observe that the poverty rates for both indicators are roughly normally distributed, with a few countries having extremely high poverty rates (above 60%) and a few countries having extremely low poverty rates (below 5%). I can also see that the poverty rates for the CIA indicator are slightly higher on average than the poverty rates for the World Bank indicator.

From the scatter plot, I can see that there is a strong positive correlation between the poverty rates according to the two indicators. This shows that countries with high poverty rates according to one indicator tend to have high poverty rates according to the other indicator as well.


Conclusion: In conclusion, the analysis provided basic descriptive statistics and visualizations of poverty rates according to two indicators - World Bank and CIA. The analysis showed that poverty rates for both indicators are roughly normally distributed, and there is a strong positive correlation between the poverty rates according to the two indicators. The poverty rates for the CIA indicator are slightly higher on average than the poverty rates for the World Bank indicator.

One limitation of the analysis is that it only considers two indicators and does not account for other factors that may contribute to poverty rates, such as income inequality, economic growth, and political stability. Future research could explore the relationship between poverty rates and these other factors to gain a more comprehensive understanding of poverty.
