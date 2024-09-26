# Phase 1 Project Description

## Project Overview
![image](https://github.com/user-attachments/assets/9dee0699-2e8b-4ad1-823e-8ef79c9de6f9)

The data is from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.
The project intend to analyze aviation accident data to uncover trends and insights that aids to improve aviation safety, inform aircraft purchases, and make informed choices. Additionally, this project aims to explore the relationships between various factors such as aircraft make/model, weather conditions, and the causes of accidents. Findings from this data will help airlines and aviation organizations make informed decisions about safety improvements, aircraft selection, and risk management.


### Business Problem Statement
The project aims to determine the key factors that causes aircrafts crash that causes fatalities in the United States.specifically, this project aims to:
 *Identify significant features that contribute to aircraft crashes.
 *Explore other correlated features to aircraft crashes.
 
The business problem entails enhancing safety, reducing accidents, and optimizing the management by identifying accident patterns related to aircraft models, weather conditions, human error, and maintenance issues.
The project analysis aims to identify risk factors, and provide actionable insights that can guide airlines, manufacturers, and regulators in improving safety, optimizing aircraft selection, and minimizing accidents. 

### Business Understanding
Have ideas on factors that significantly contribute to aircraft crashes.
Create visualizations that will represent the findings from my analyzed data.The key questions are:
 *Which aircraft makes/models are associated with the highest or lowest fatalities?
 *Which aircraft models are more prone to accidents?
 *How do different weather conditions affect accident rates?
 *What are the main causes of accidents such as mechanical failure?

#### Data Analysis
Entails data cleaning which involves converting necessary columns to numeric types, handle missing data, removing duplicates, outliers and unneccesary rows. In addition, the data should be aggregated to acquire totals for the varibles and grouped relevant data categories.

#### Exploratory Data Analysis (EDA)
The EDA that was mostly used was descriptive statistics to calculate mean, median, and standard deviation. It was also used to calculate accident distribution by aircraft model and weather conditions.
The visualizations used were:
*The heatmap to show the correlation between injuries and survivals. ![image](https://github.com/user-attachments/assets/6e640117-bf80-425b-ac24-4135785e0975). Dark colors indicate a strong positive correlation, meaning that as injuries increase, fatalities also rise. Light colors or neutral tones suggest weak or no correlation between the variables. It also helps in identifying patterns in the data, such as whether more severe injuries are associated with fewer survivors.

*The bar chart to visualize the frequency of accidents by aircraft model. Each bar represents an aircraft model, and the height of the bar corresponds to the number of accidents for that model. Taller bars indicate models with higher accident frequencies, while shorter bars represent models with fewer accidents. This type of chart helps in identifying which aircraft models have been involved in more accidents and may provide insights into safety patterns across different aircraft. ![image](https://github.com/user-attachments/assets/0624af18-84cf-46b8-8a96-acd213cbf888)

*The histogram to analyze the distribution of fatalities of aircraft engine types. The x-axis represents the range of fatalities for each engine type, often grouped into bins (ranges of fatalities). The y-axis shows the number of occurrences within each bin, indicating how many instances of fatalities fall into that range. This kind of visualization helps to identify patterns in fatalities across different engine types, highlighting which engines are associated with more or fewer fatalities. ![image](https://github.com/user-attachments/assets/a17472d5-5a54-487c-82f6-8ef721c4e552)

*The box plot was to show the outliers, the total fatal injuries caused by various aircrafts under various weather conditions. Each box represents the interquartile range (IQR), which contains the middle 50% of the data. The line inside the box shows the median number of fatal injuries for each weather condition. Whiskers extend from the box, indicating the range within 1.5 times the IQR. Dots outside the whiskers represent outliers, which are instances where the total fatal injuries are significantly higher or lower than the majority of the data. This boxplot helps identify how weather conditions relate to fatal injuries and highlights any extreme cases.![image](https://github.com/user-attachments/assets/17f6c259-421a-4c38-b32d-97e48154e2ee)

*The pie chart visualizes the distribution of weather conditions and fatalities caused on that particular weather. The slices in this pie chart represents a different weather condition e.g., VMC, IMC etc. The size of each slice indicates the relative frequency of fatalities occurring under that particular weather condition. The labels on the chart or within the slices provide the percentage of total fatalities attributed to each weather category. This viz helps highlight which weather conditions are most commonly associated with fatal accidents, giving insights into potential risks tied to specific environmental factors.![image](https://github.com/user-attachments/assets/4931eb1f-3397-4786-bf36-149282f69cc4)

    
### Non-Technical Presentation
Analyzing historical aviation accident data can predict patterns on which aircraft models are safer, how weather impacts flight safety, and what factors contribute to most accidents. Based on these ideas, it can help airlines, manufacturers, and regulators make an informed choice that will improve the overall safety while minimizing future risks.

### Business Success Criteria
For the business to be a sucess, it should achieved most or all of the following demands to curb accidents:
*Enhanced aircraft safety.
*Accurate identification of risk factors.
*Improved weather planning and response.
*Have achieved cost reduction such as operational costs, maintenance, insurance, and liability expenses.

### Recommendations
For the commercial purposes, the airlines should focus on purchasing aircraft models with strong safety records based on the analyzed data.
Improve weather-related safety accidents such as pilot training for adverse conditions, upgrade weather monitoring systems, regular aircraft maintenance especially the engines, and focus on allievating human error.

### Next steps
More research should be done to create predictive models that will tell the likelihood of an accident by various factors.
Test and implement the recommendations.
Report and communicate the findings.
Intergrate the feedback and and iterate.
Initiate long-term study on safety trends.

### Interactive Dashboard
Dashboards are interactive visualizations that tend to explain or analyze data to show trends in business. They are essential tools because they improve analyzed data, which is key to making an informed decision. Here is a link to tableau dashboard about aviation accidents: https://public.tableau.com/app/profile/margret.nyairo/viz/ProjectPhase1Dashboard_17273026172260/SummaryofAircraftAccidents?publish=yes.

### Summary
This dataset comprises records of aviation accidents and incidents from various states in the USA, detailing factors such as accident severity, weather conditions, and aircraft information. It provides crucial insights into aviation safety, allowing analysts to investigate correlations between weather, aircraft types, and accident outcomes. These insights will enhance stakeholders to implement necessary precautions for future trends.
