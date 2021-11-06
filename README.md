# DataScienceProjects
This page is a list of the Data Science projects I have been working on. 

## 1.Double Machine Learning (DML) Application & Visualization 
### Internship Project @Microsoft
Successfully improved Microsoft Office product suite usage using Double Machine Learning (DML) and reduced internal client COGS by 40% by developing a visualization framework.
- Implemented DML to resolve inherent confounding issues by finding the causal estimate between product feature usage and Net Promoter Score.
- Collaborated across office teams to model the impact of app performance duration on customer satisfaction level for multiple office products.
- Improved SLA and customer satisfaction by analyzing DML causal estimate results.
- Designed and developed a visualization framework using Python and Azure Web Service to analyze the causal relationship between feature usage, app responsiveness and NPS flux. Removed redundancy of work by partner teams to visualize DML results and enabled teams to prioritize product improvement features with an improved cost-effective time management strategy.   
   
Used: Python, Dash, Azure Web Service, Cosmos, Databrick, Spark, Scala, PowerShell

## 2. Comparison of Unsupervised Clustering Algorithms for Market Segmentation via Heterogeneous Data
### Current Capstone Project @Milliman
In this project, we will be applying several unsupervised clustuering algorithms, defined in the [paper](https://www.nature.com/articles/s41598-021-83340-8), to produce market segmentation, identifying or developing metrics to compare the results we obtain such that the product team could possibly create improved personas or validate the set of personas already obtained.

## 3. Fruits Image Classification Performance Comparison between Local and Azure Databricks
This is a current academic project that we will compare the TensorFlow performance on Local machine and Azure Databrick via Python and PySpark. The dataset of Fruit Recognition is obtained from [Kaggle.com] (https://www.kaggle.com/chrisfilo/fruit-recognition), which includes 44,406 fruit images in .png format. The size of this dataset is 8.49GB.   
   
We will make a comparison on the runtime difference for image classification via Python and PySpark on Local machine via 1G and 3G dataset. then we will continue comparint the runtime difference on Azure Databrick via Python and PySpark between different numbers of works by applying the algorithm on the whole dataset.    


## 4. [Parking App](https://github.com/anushnap/seattlepark)
Created an interactive API using the Seattle Annual Parking Study, which records street parking usage at various times of day on streets throughout the city to create a suggestion for most-likely-available streets to park in based on a user’s inputted destination.  
   
The app will accpet destination address and accpetable walking distances as input. The destination address will be converted to coordinates by calling Google Map API. We will then calculated the distance between the destination and all the other streets in the database and filtere by the acceptable distance to select the top 20 closest streets and pass their coordinates to the recommendation engine.    
   
The recommendation engine will take the 20 closest streets' coordinates as well as the datetime when the user submit the query as input, compare them to the history data to caculate the maximum estimate free spaces on each street and return the top 5 streets with the highest estimated availability. 
   
The map will be updated with the top 5 recommended streets. For each recommended street, hover information via figure shows the street address with an embedded Google Map link, distance from the destination and the number of spaces available. Once user clicks the Google Map link, it will launch Google Map experience to provide the user with directions to the intended parking spot.    
   
- Improved parking spot visibility and navigability by finding parking spots anywhere in the world.
- Provides number of available spots by time of day, destination address and walking distance on a street.
- Used: Python, Dash, Plotly, GitHub, HTML, Heroku, Google Map API.  
   
![Architecture](/Users/jane/Desktop/1.png?raw=true "Architecture")  
![MapView](/Users/jane/Desktop/2.png?raw=true "MapView") 

## 5. [Police Gun Violence Visualization](https://public.tableau.com/app/profile/qiaohui.sun/viz/PoliceViolenceintheUnitedStates2013-2019_16077210133780/Final_Concept)  
Our goal of this project is to create a detailed visualization that would enable our users to gain insight into police violence in the United States. We aim at giving our users a comprehensive understanding into the trend of police killings from 2013 - 2019 and the racial disparity in those killings. Our visualization will also shed light on the legal statuses of police officers involved in violence against civilians and hope that will spark a conversation on the importance of police reform and creating policy solutions that are aimed at ending police violence in the US.   
   
The intended audience for our visualization are both the general public, who are interested in gaining knowledge into police brutality, as well as activists who work on creating policy proposals for police reform.   
   
Used: Python, Tableau, Pandas and Anaconda

## 6. Gender Disparity in Access to Education
This analysis focuses on three areas to evaluate the education disparity between girls and boys as well as the out of school rate
for girls. The first focus area investigates the magnitude of education disparity in addition to the out of school rate by country and income level. The second focus investigates the associations between human and women’s rights in relation to both the gender parity index and the out of school rate for girls. The third focus is on the relationship between several factors which could influence the out of school rate for girls. Access to girls education is a large problem with many factors; however, by investigating the magnitude, importance, and potential influencers associated with education disparity and improving access to education for girls the problem can start to be addressed.  
   
Used: Linear Regression, Python, R Studio, Tableau
   
![Architecture](/Users/jane/Desktop/1.png?raw=true "Architecture")  
![MapView](/Users/jane/Desktop/2.png?raw=true "MapView") 


