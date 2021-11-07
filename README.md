# DataScienceProjects
This page is a list of the Data Science projects I have been working on. 

## 1.Double Machine Learning (DML) Application & Visualization 
### Internship Project @Microsoft
![dml](https://github.com/qhsun/DataScienceProjects/blob/main/images/dml.png?raw=true)  

Successfully improved Microsoft Office product suite usage using Double Machine Learning (DML) and reduced internal client COGS by 40% by developing a visualization framework.
- Implemented DML to resolve inherent confounding issues by finding the causal estimate between product feature usage and Net Promoter Score.
- Collaborated across office teams to model the impact of app performance duration on customer satisfaction level for multiple office products.
- Improved SLA and customer satisfaction by analyzing DML causal estimate results.
- Designed and developed a visualization framework using Python and Azure Web Service to analyze the causal relationship between feature usage, app responsiveness and NPS flux. Removed redundancy of work by partner teams to visualize DML results and enabled teams to prioritize product improvement features with an improved cost-effective time management strategy.   
      
Used: Python, Dash, Azure Web Service, Cosmos, Databrick, Spark, Scala, PowerShell

## 2. Comparison of Unsupervised Clustering Algorithms for Market Segmentation via Heterogeneous Data
### Current Capstone Project @Milliman
In this project, we will be applying several unsupervised clustuering algorithms, defined in the [research paper](https://www.nature.com/articles/s41598-021-83340-8). The goal of the project is to find the most optimal market segment by comparing the results of the clustering algorithms. A comparison analysis would be performed between the new segmanetation and an existing market segmentation in Milliman. The evaluated comparison metrics would help Milliman clients to improve or validate persona of a market segment.
   
Used: Python, PySpark, Azure Databricks

## 3. Fruits Image Classification Performance Comparison between Local and Azure Databricks
The project intends to compare the TensorFlow performance on Local machine and Azure Databricks via Python and PySpark. The dataset for Fruit Recognition is obtained from [Kaggle.com] (https://www.kaggle.com/chrisfilo/fruit-recognition), which includes 44,406 fruit images in .png format. The size of this dataset is 8.49GB.   

This project is two-fold:
- In the first part it discuss Python vs Pyspark performance for TensorFlow through various hyperparameters on local with a relatively decent sized data (about 1GB csv file). Additionally, it also discusses how performance for data preparation tasks changes for different size of datasets on local Python and PySpark (1GB vs 3GB)
- In the second part, we tune these parameters and understand the performance of pyspark on Azure Databricks cluster with different nodes and partitions using a much larger dataset (~8.49GB).
   
Used: Python, PySpark, TensorFlow, Azure Databricks


## 4. Parking App
![Architecture](https://github.com/qhsun/DataScienceProjects/blob/main/images/parkingarchitecture.png?raw=true)  
![MapView](https://github.com/qhsun/DataScienceProjects/blob/main/images/parkingmap.png?raw=true)   

Created an interactive API using the Seattle Annual Parking Study, which records street parking usage at various times of day on streets throughout the city to create a suggestion for most-likely-available streets to park in based on a user’s inputted destination.  
   
The app accpets destination address and accpetable walking distances as input. The destination address is converted to coordinates by calling Google Map API. We then calculated the distance between the destination and all the other streets in the database and filtered by the acceptable distance to select the top 20 closest streets and passed their coordinates to the recommendation engine.    
   
The recommendation engine takes the 20 closest streets' coordinates as well as the datetime when the user submitted the query as input, compared them to the history data to caculate the maximum estimate free spaces on each street and returned the top 5 streets with the highest estimated availability. 
   
The map is updated with the top 5 recommended streets. For each recommended street, hover information showed the street address with an embedded Google Map link, distance from the destination and the number of spaces available. Once user clicked the Google Map link, it launched Google Map experience to provide the user with directions to the intended parking spot.    
   
Used: Python, Dash, Plotly, GitHub, HTML, Heroku, Google Map API.  

## 5. Police Gun Violence Visualization([Viz](https://public.tableau.com/app/profile/qiaohui.sun/viz/PoliceViolenceintheUnitedStates2013-2019_16077210133780/Final_Concept))  
![viz](https://github.com/qhsun/DataScienceProjects/blob/main/images/gunviolence.png?raw=true)   

Goal of this project was to create a detailed visualization that would enable our users to gain insight into police violence in the United States. We aimed at giving our users a comprehensive understanding into the trend of police killings from 2013 - 2019 and the racial disparity in those killings. The visualization also shed light on the legal statuses of police officers involved in violence against civilians and hoped to spark a conversation on the importance of police reform and creating policy solutions that are aimed at ending police violence in the US.   
   
Used: Python, Tableau, Pandas and Anaconda   
 

## 6. Gender Disparity in Access to Education
![result](https://github.com/qhsun/DataScienceProjects/blob/main/images/eduresult.png?raw=true)  
![map](https://github.com/qhsun/DataScienceProjects/blob/main/images/eduviz.png?raw=true) 

This analysis focused on three areas to evaluate the education disparity between girls and boys as well as the out of school rate
for girls. The first focus area investigated the magnitude of education disparity in addition to the out of school rate by country and income level. The second focus investigated the associations between human and women’s rights in relation to both the gender parity index and the out of school rate for girls. The third focus was on the relationship between several factors which could influence the out of school rate for girls. Access to girls education is a large problem with many factors; however, by investigating the magnitude, importance, and potential influencers associated with education disparity and improving access to education for girls, can trigger the initiative to address the problem.  
   
Used: Linear Regression, Python, R Studio, Tableau  
   



