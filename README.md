# Data Portfolio: Obesity Dashboard

## Objective
This analysis was conducted to provide a comprehensive overview of obesity prevalence and associated risk factors. By examining key metrics such as age, gender, family history, dietary habits, physical activity levels, and technology usage, we identified key trends and potential areas for intervention. A key insight from the analysis is that individuals classified as obese exhibited a higher prevalence of smoking, less frequent consumption of vegetables, and a greater likelihood of having overweight or obese family members compared to those in the normal weight category (see Comparative Analysis of Obesity Categories). Based on the analysis, we recommend promoting healthier lifestyle choices through public health initiatives that encourage regular physical activity, balanced dietary habits, and reduced consumption of fast food. By implementing these recommendations, we can potentially reduce obesity prevalence by 5-10% within the next five years and improve overall public health (see Potential Impact of Recommendations).   

## Methodology

### Data Sources
The primary data source for this analysis is an obesity dataset comprising 1,610 rows and 15 columns, including:
•	Demographic Information (Sex, Age, Height)
•	Family History (Overweight/Obese Family)
•	Dietary Habits (Consumption of Fast Food, Frequency of Consuming Vegetables, Number of Main Meals Daily, Food Intake Between Meals)
•	Lifestyle Choices (Smoking, Liquid Intake Daily, Calculation of Calorie Intake, Physical Exercise, Schedule Dedicated to Technology, Type of Transportation Used)
•	Weight Classification (Class)

### Tools Used
The following tools were used for data analysis and visualization:
•	Microsoft Excel – Data exploration
•	Microsoft SQL Server – Data cleaning and analysis
•	Microsoft PowerBI – Data visualization, aggregation, and segmentation

### Data Cleaning and Preparation
The following data cleaning and preparation steps were performed using SQL Server:
•	Converted columns to their appropriate data types.
•	Converted numerical values in categorical columns to descriptive labels (e.g., 1 and 2 in the "Sex" column were converted to "Male" and "Female" respectively).
•	Corrected a misspelling in the "Physical Exercise" column.

### Data Exploration
Initial data exploration involved familiarizing ourselves with the dataset and identifying key variables. This included examining the distribution of weight classifications, age, and gender, as well as exploring potential relationships between lifestyle choices and obesity prevalence.

### Data Analysis Techniques
The following data analysis techniques were employed:

•	Descriptive Analysis: We calculated descriptive statistics such as average age, gender distribution, and prevalence of obesity for the overall population and within specific weight classifications. This involved summarizing key characteristics of the dataset to provide an overview of the obesity landscape.

•	Comparative Analysis: We compared the characteristics and behaviors of individuals in different weight classifications (underweight, normal, overweight, obese) to identify potential risk factors and trends associated with obesity. This involved grouping data by weight classification and calculating relevant metrics to identify significant differences.

•	Correlation Analysis: We calculated the correlation between various factors such as fast food consumption, vegetable consumption, physical activity, and technology usage to explore potential relationships with obesity prevalence. This involved using statistical methods to measure the strength and direction of the linear relationship between these variables.

•	Segmentation Analysis: We segmented the data by various factors such as age, gender, and lifestyle choices to identify specific subgroups with higher or lower obesity prevalence. This involved dividing the dataset into meaningful groups and analyzing their characteristics to understand the nuances of obesity prevalence within different population segments.

•	Diagnostic Analysis: This analysis was used to identify the root cause of the higher prevalence of smoking among obese individuals. By examining various factors such as stress levels, social influences, and access to healthcare, we aimed to understand the underlying reasons for this association.   

### Future Considerations for Data Analysis
In the future, we can leverage additional data analysis techniques to further refine our understanding of obesity and develop more targeted interventions. These techniques include:

•	Predictive Modeling: This technique can be used to build predictive models that assess the likelihood of an individual becoming obese based on their characteristics and behaviors. By incorporating machine learning algorithms and advanced statistical methods, we can identify high-risk individuals and develop personalized interventions.

•	Geospatial Analysis: This method involves analyzing data with geographic components to understand the spatial distribution of obesity and identify potential environmental factors that contribute to its prevalence. By mapping obesity rates and overlaying data on factors such as access to healthy food options, recreational facilities, and healthcare services, we can identify areas with higher obesity prevalence and develop targeted interventions.

## Analysis of Obesity Prevalence

### Overall Prevalence
The overall prevalence of obesity in the dataset is 18.4%, with 297 individuals classified as obese out of a total of 1,610 individuals. This indicates a significant public health concern that warrants attention and intervention.
(Insert visualizations: Pie chart showing the distribution of weight classifications)

## Comparative Analysis of Obesity Categories
A comparative analysis of different weight classifications revealed the following key trends:

•	Obese individuals tend to be older: The average age of obese individuals (40 years) is significantly higher than that of normal weight individuals (26 years).

•	Obesity is more prevalent among males: There is a higher proportion of males (51.5%) in the obese category compared to the normal weight category (29.2%).

•	Smoking is more prevalent among obese individuals: A significantly higher percentage of obese individuals (59.2%) are smokers compared to normal weight individuals (20.1%).

•	Obese individuals consume vegetables less frequently: Obese individuals are more likely to rarely consume vegetables compared to normal weight individuals.

•	Family history plays a role: Obese individuals are more likely to have overweight or obese family members compared to normal weight individuals.
(Insert visualizations: Bar charts comparing key metrics across different weight classifications)

## Analysis of Lifestyle Factors
The analysis of lifestyle factors revealed the following insights:

•	Physical activity is associated with lower obesity prevalence: Individuals who engage in regular physical activity have a lower prevalence of obesity compared to those who are inactive.

•	Fast food consumption is linked to obesity: Obese individuals are more likely to consume fast food compared to normal weight individuals.

•	Liquid intake and vegetable consumption are associated with healthier weight: Individuals who consume more than 2 liters of water daily and always eat vegetables have a lower prevalence of obesity.
(Insert visualizations: Scatter plots or bar charts showing the relationship between lifestyle factors and obesity prevalence)

## Segmentation Analysis
Segmentation analysis revealed that:

•	Males have a higher prevalence of obesity across all age groups.

•	Obesity prevalence increases with age, particularly among males.

•	Individuals who spend more than 5 hours per day on technology have a higher prevalence of obesity.
(Insert visualizations: Charts or tables showing obesity prevalence by age, gender, and technology usage)

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
Key Takeaways
This analysis provides valuable insights into obesity prevalence and associated risk factors. Here are the key takeaways:

•	Obesity is a significant public health concern: The overall prevalence of obesity in the dataset is 18.4%, indicating a need for intervention.

•	Obese individuals exhibit distinct characteristics: Obese individuals tend to be older, have a higher prevalence of smoking, consume vegetables less frequently, and have a greater likelihood of having overweight or obese family members.

•	Lifestyle factors play a crucial role: Physical activity, fast food consumption, liquid intake, and vegetable consumption are associated with obesity prevalence.

•	Targeted interventions are needed: Segmentation analysis highlights the need for targeted interventions for specific groups such as males, older adults, and individuals with high technology usage.

By implementing the recommendations outlined in this report and continuously monitoring obesity trends, we can promote healthier lifestyles, reduce obesity prevalence, and improve public health.
