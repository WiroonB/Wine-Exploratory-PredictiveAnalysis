## Wine Exploratory and Predictive Analysis(R)

Data science project completed using R as part of school project.

### Overview
We are working with a dataset of more than 6000 different wines, including both red and white wines. For those interested in wine and particularly wine consumption, our project will help wine aficionados make informed decisions when choosing wine and help understand factors that help explain qualitative wine levels. By converting the numerical qualitative field to categorical we can than make distinctions between higher and lower quality wines as well as see variances between red and white based on quality.

 **Exploratory Analysis** focuses on breif description about the topic, data source as well as variables with descriptive statistics of dataset. Here are some of the questions that are used to explore:
 
  - How does your project help those who are interested in this topic?
  - Why data analysis is needed for this?
  - How do you expect your analysis to improve decision making in this area?
  - What is the source?
  - What are your variables? If there are too many, focus on the ones that you will explore
  - Describe the data cleaning process if you needed
  - What is the distribution of wine in the data set? Red vs White & Quality?
  - What variables determine quality of wine?
  - Are there differences between white and red wine that are more informative where variables can determine white or red?


**Predictive Analysis** focuses on constructing predictive model which includes model building and model results. 
  - Based on question 2 & 3, volatile acidity and alcohol are the strongest variables that determine quality of wine. What is the relationship between volatile acidity and alcohol in wine?
  - After finding no significant relationship between volatile acidity and alcohol, can we find that there is a stronger relationship between alcohol & quality?


| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Wine-Exploratory-PredictiveAnalysis-R/blob/main/Group_Project_files/figure-gfm/unnamed-chunk-2-1.png?raw=true"> Win Distribution | <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Wine-Exploratory-PredictiveAnalysis-R/blob/main/Group_Project_files/figure-gfm/unnamed-chunk-3-1.png?raw=true"> Win Variables  | <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Wine-Exploratory-PredictiveAnalysis-R/blob/main/Group_Project_files/figure-gfm/unnamed-chunk-4-1.png?raw=true"> Wine Variables |
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Wine-Exploratory-PredictiveAnalysis-R/blob/main/Group_Project_files/figure-gfm/unnamed-chunk-4-2.png?raw=true"> Wine Varibles  |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Wine-Exploratory-PredictiveAnalysis-R/blob/main/Group_Project_files/figure-gfm/unnamed-chunk-5-1.png?raw=true"> Volatile Acidity and Alcohol | <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Wine-Exploratory-PredictiveAnalysis-R/blob/main/Group_Project_files/figure-gfm/unnamed-chunk-6-1.png?raw=true"> Quality and Alcohol|

**Summary of Findings & Prediction Method**

Our prediction method is based on finding the following variables will best predict quality of wine:
 * Volatile Acidity
 * Residual Sugar
 * Free sulphur dioxide & total sulphur dioxide
 * Sulphates
 * Alcohol




