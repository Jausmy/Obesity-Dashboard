# Data Portfolio: Obesity Dashboard

![Project-Main-Image](Assets/Images/Obesity%20Main%20Image.jpg)

## Objective
This report presents a comprehensive analysis of obesity prevalence and associated risk factors. By examining demographic data, lifestyle choices, and health-related behaviors, we aim to identify key trends and provide actionable insights to promote healthier lifestyles and reduce obesity rates.

## Executive Summary
We've identified key trends and possible key areas for intervention that may reduce the prevalence of obesity among the population. Key insights from the analysis show that individuals classified as obese exhibited a higher prevalence of smoking, less frequent consumption of vegetables, and a greater likelihood of having overweight or obese family members compared to those in the normal weight category [(see Comparative Analysis of Obesity Categories)](#Comparative-Analysis-of-Obesity-Categories). Based on the analysis, we recommend promoting healthier lifestyle choices through public health initiatives that encourage regular physical activity in combination with balanced dietary habits, and reduced consumption of fast food. By implementing these recommendations, we can potentially reduce obesity prevalence by 5-10% within the next five years and improve overall public health [(see Potential Impact of Recommendations)](#Potential-Impact-of-Recommendations).   

## Methodology
### Data Sources
The primary data source for this analysis is an obesity sample dataset comprising of 1,610 rows and 15 columns, including:

•	Demographic Information (Sex, Age, Height)

•	Family History (Overweight/Obese Family)

•	Dietary Habits (Consumption of Fast Food, Frequency of Consuming Vegetables, Number of Main Meals Daily, Food Intake Between Meals)

•	Lifestyle Choices (Smoking, Liquid Intake Daily, Calculation of Calorie Intake, Physical Exercise, Schedule Dedicated to Technology, Type of Transportation Used)

•	Weight Classification (Class)

Each row in the dataset represents a unique individual and their responses to the corresponding column.

![Data Source](Assets/Images/Obesity%20-%20Data%20Source.png)

![Data-Source-2](Assets/Images/Obesity%20-%20Data%20Source%202.png)

### Tools Used
The following tools were used for data analysis and visualization:

•	Microsoft Excel – Data familiarization

•	Microsoft SQL Server – Data cleaning and exploration/analysis

•	Microsoft PowerBI – Data visualization, aggregation, and segmentation

### Data Cleaning and Preparation
The following data cleaning and preparation steps were performed using SQL Server:

•	Converted columns to their appropriate data types.

•	Converted numerical values in categorical columns to descriptive labels (e.g. 1 and 2 in the "Sex" column were converted to "Male" and "Female" respectively).

•	Corrected a misspelling in the "Physical Exercise" column.

![SQL-Code](Assets/Images/Obesity%20-%20Data%20Cleaning%202.png)

![SQL-Code-2](Assets/Images/Obesity%20-%20Data%20Cleaning%203.png)

![SQL-Code-3](Assets/Images/Obesity%20-%20Data%20Cleaning%204.png)

![SQL-Code-4](Assets/Images/Obesity%20-%20Data%20Cleaning%205.png)

![SQL-Code-5](Assets/Images/Obesity%20-%20Data%20Cleaning%206.png)

### Data Exploration
Initial data exploration involved familiarizing ourselves with the dataset and identifying key variables. This included examining the distribution of weight classifications, age, and gender, as well as exploring potential relationships between lifestyle choices and obesity prevalence.

### Data Analysis Techniques
The following data analysis techniques were employed:

•	Descriptive Analysis: We calculated descriptive statistics such as average age, gender distribution, and prevalence of smokers for the overall population. This involved summarizing key characteristics of the dataset to provide an overview of the obesity landscape.

![Overall-KPIs](Assets/Images/Obesity%20-%20Overall%20KPIs.png)

•	Comparative Analysis: We compared the characteristics and behaviors of individuals in different weight classifications (underweight, normal, overweight, obese) to identify potential risk factors and trends associated with obesity. This involved grouping data by weight classification and calculating relevant metrics to identify significant differences.

## Future Considerations for Data Analysis
In the future, we can leverage additional data analysis techniques to further refine our understanding of obesity and develop more targeted interventions. These techniques include:

•	Predictive Modeling: This technique can be used to build predictive models that assess the likelihood of an individual becoming obese based on their characteristics and behaviors. By incorporating machine learning algorithms and advanced statistical methods, we can identify high-risk individuals and develop personalized interventions.

•	Geospatial Analysis: This method involves analyzing data with geographic components to understand the spatial distribution of obesity and identify potential environmental factors that contribute to its prevalence. By mapping obesity rates and overlaying data on factors such as access to healthy food options, recreational facilities, and healthcare services, we can identify areas with higher obesity prevalence and develop targeted interventions.

## Analysis of Obesity Prevalence
### Overall Prevalence
The overall prevalence of obesity in the dataset is 18.4%, with 297 individuals classified as obese out of a total of 1,610 individuals. This indicates a significant public health concern that warrants attention and intervention.

![Obesity-KPIs](Assets/Images/Obesity%20-%20Obese%20KPIs.png)

## Comparative Analysis of Obesity Categories
A comparative analysis of different weight classifications revealed the following key trends:

•	Obese individuals tend to be older: The average age of obese individuals (40 years) is significantly higher than that of normal weight individuals (26 years).

![Normal-KPIs](Assets/Images/Obesity%20-%20Normal%20KPIs.png)

•	Obesity is more prevalent among males: There is a higher proportion of males (53.0%) in the obese category compared to the normal weight category (28.6%).

![Obesity-Gender-Graph](Assets/Images/Obesity%20-%20Obese%20Gender%20Graph.png)

![Normal-Gender-Graph](Assets/Images/Obesity%20-%20Normal%20Gender%20Graph.png)

•	Smoking is more prevalent among obese individuals: A significantly higher percentage of obese individuals (59.2%) are smokers compared to normal weight individuals (20.1%).

![Obese-Smokers](Assets/Images/Obesity%20-%20Obese%20Smokers.png)

![Normal-Smokers](Assets/Images/Obesity%20-%20Normal%20Smokers.png)

•	Obese individuals consume vegetables less frequently: Obese individuals are more likely to rarely consume vegetables compared to normal weight individuals.

![Obese-Liq-Veg](Assets/Images/Obesity%20-%20Obese%20Liquid%20&%20Vegetables.png)

•	Family history plays a role: Obese individuals are more likely (42.5%) to have overweight or obese family members compared to normal weight individuals (8.1%).

![Obese-Family-History](Assets/Images/Obesity%20-%20Obese%20Family%20Graph.png)

![Normal-Family-History](Assets/Images/Obesity%20-%20Normal%20Family%20Graph.png)

## Analysis of Lifestyle Factors
The analysis of lifestyle factors revealed the following insights:

•	A higher percentage of obese individuals (83.6%) report exercising regularly (3 days or more a week) compared to normal weight individuals (60.8%). This observation alone does not explain the relationship between physical activity, diet, and obesity..

•	Fast food consumption is linked to obesity: Obese individuals are more likely to consume fast food compared to normal weight individuals.

![Obese-Exercise](Assets/Images/Obesity%20-%20Obese%20Physical%20Exercise.png)

•	Liquid intake and vegetable consumption are associated with healthier weight: Individuals who reported consistent consumption of vegetables exhibited the lowest observed obesity prevalence (0%), while those who consumed more than 2 liters of water daily had an obesity prevalence of 10.9% (compared to 23% for less than 1L and 21.8% for between 1L and 2L).

![Normal-Liq-Veg](Assets/Images/Obesity%20-%20Obese%20Liquid%20&%20Vegetables.png)

## Segmentation Analysis
Segmentation analysis revealed that:

•	Males have a higher prevalence of obesity.

•	Obesity prevalence increases with age, particularly among males.

## Recommendations
Based on the analysis of obesity prevalence and associated risk factors, the following recommendations are proposed:

•	Promote Healthy Lifestyles: Implement public health initiatives that encourage regular physical activity, balanced dietary habits, and reduced consumption of fast food. This could involve public awareness campaigns, community programs, and educational interventions in schools and workplaces.

•	Target High-Risk Groups: Develop targeted interventions for high-risk groups such as males, older adults, and individuals with a family history of obesity. This could involve personalized health counseling, community-based weight management programs, and access to affordable healthy food options.

•	Address Smoking Cessation: Integrate smoking cessation programs into obesity prevention and management strategies, considering the high prevalence of smoking among obese individuals.

•	Encourage Vegetable Consumption: Promote the importance of regular vegetable consumption through educational campaigns and initiatives that increase access to affordable fresh produce.

•	Limit Technology Usage: Raise awareness about the potential link between excessive technology usage and obesity, and encourage healthy alternatives such as outdoor activities and physical exercise.

## Potential Impact of Recommendations
By implementing these recommendations, we can anticipate the following positive outcomes:

•	Reduced Obesity Prevalence: Promoting healthier lifestyles and targeted interventions can potentially reduce obesity prevalence by 5-10% within the next five years.

•	Improved Public Health: Reducing obesity rates can lead to a decrease in related health issues such as heart disease, diabetes, and certain types of cancer, ultimately improving overall public health.

•	Reduced Healthcare Costs: Lower obesity prevalence can translate to reduced healthcare costs associated with treating obesity-related diseases.

## Limitations and Future Considerations
While this analysis provides valuable insights and recommendations, it's important to acknowledge certain limitations:

•	Data Availability: The analysis is limited by the available data. Access to more detailed information on individual medical history, genetic factors, and socioeconomic status would allow for a more comprehensive analysis.

•	Causation vs. Correlation: While the analysis identifies correlations between certain factors and obesity prevalence, it does not necessarily imply causation. Further research is needed to establish causal relationships and develop more effective interventions.

## Key Takeaways
This analysis provides valuable insights into obesity prevalence and associated risk factors. Here are the key takeaways:

•	Obesity is a significant public health concern: The overall prevalence of obesity in the dataset is 18.4%, indicating a need for intervention.

•	Obese individuals exhibit distinct characteristics: Obese individuals tend to be older, have a higher prevalence of smoking, consume vegetables less frequently, and have a greater likelihood of having overweight or obese family members.

•	Lifestyle factors play a crucial role: Physical activity, fast food consumption, liquid intake, and vegetable consumption are associated with obesity prevalence.

•	Targeted interventions are needed: Segmentation analysis highlights the need for targeted interventions for specific groups such as males, older adults, and individuals with high technology usage.

By implementing the recommendations outlined in this report and continuously monitoring obesity trends, we can promote healthier lifestyles, reduce obesity prevalence, and improve public health.
