![Car-Sales-Increase-In-India](https://github.com/mesege1/stats_case_study/assets/135185712/11b259fd-e5ed-4868-a5d3-9034a6e6798e)
# Hypothesis Testing for Relationship between Weight and MPG
This project aims to investigate whether there is a statistically relationship between the weight and MPG (Miles Per Gallon) of vehicles.
# Data
The analysis is based on a sample dataset of car data from 1970 to 1982 provided by Galvanize learning. The data is in the 'data' folder as 'car_data.csv'.
# Hypotheses
Our team tested the following hypotheses:
1. Null Hypothesis: There is no statistically significant linear relationship between the weight and MPG of vehicles in the population. 
2. Alternative Hypothesis: There is a statistically significant linear relationship between the weight and MPG of vehicles in the population.
# Step for Analysis
1. Load data: The data is loaded into a pandas data frame for further analysis.
2. Create the sample size from the population under comlumns of 'MPG' & 'Weight': We generated random samples from the data to prepare for performing hypothesis testing.
4. Calculate correlation: Using 'T-Test', we computed correlation coefficient and p-value to measure the significance of the relationship.
5. Scatter plotting: We plotted 'MPG' and 'Weight' items on scatter plot, and added correlation line. 
# Hypothesis Testing
The correlation test determines whether the null hypothesis can be rejected based on the p-value and significance level.
# Hypothesis Testing Result
- Result: -0.831741
- Explanation: A correlation coefficient close to +1 or -1 indicates a strong linear relationship between the two variables. 
# Visualization
Scatter plot and histograms are used to visualize the distribution of correlation coefficients and p-values.
1. Scatter plot & Correlation
![scatter_with_corr_line_with_sns_theme_without_y_ticks](https://github.com/mesege1/stats_case_study/assets/135185712/64d51c40-6690-4c71-a33a-34b86e3e257d)
2. Sampling Distribution of the mean MPG
![sample_distribution_mpg](https://github.com/mesege1/stats_case_study/assets/135185712/aef91e8c-b7c7-48ac-a510-4268a826c7f4)
3. Sampling Distribution of the mean weight
![sample_distribution_weight](https://github.com/mesege1/stats_case_study/assets/135185712/117658d8-b571-45a1-b31a-c51465bf4392)
# Conclusion
- The correlation coefficient of -0.831741 between MPG and weight suggests a strong negative linear relationship between these two variables in the population. The negative sign of the correlation coefficient indicates that as the weight of a vehicle increases, its MPG tends to decrease.
- Overall, the negative correlation coefficient of -0.831741 indicates a strong and statistically significant inverse relationship between weight and MPG in the population of vehicles represented in the dataset.
