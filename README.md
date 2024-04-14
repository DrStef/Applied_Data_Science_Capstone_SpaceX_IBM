##### Applied Data Science Capstone: 
This project is part of IBM Data Science certificate. https://www.coursera.org/professional-certificates/ibm-data-science

<p align="center">
<img src="https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/spacex-MEW1f-yu2KI-unsplash.jpg" width="480" height="264" />
  

# SpaceX Falcon 9 First Stage Landing Prediction

In this project, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. In this lab, you will collect and make sure the data is in the correct format from an API. The following is an example of a successful and launch.
This supervised classification project was carried out as part of the IBM Data Science Professional certificate.


### **Presentation of the project** 

The presentation covers all steps described in Jupyter Notebooks in following sections. From Data Collection, Analysis to prediction of launch succeess (succesful first stage landing) with classification algorithms. We draw a parallel between SpaceX Falcon9 and ArianeEspace Ariane5 (and coming Ariane6) that was dominating the market of commercial launches until SpaceX put an end to this domination thanks to the reusable boosters concept and induced cost reduction.     


#### <ul>[Presentation - pdf](https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/Stephane_Dedieu_ds-capstone-template-coursera_v9.pdf)</ul>

Presentation to be downloaded (15.6MB). Will not display on Github. 
#### <ul>[Presentation - pptx](https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/Stephane_Dedieu_ds-capstone-template-coursera_v9.pptx)</ul>

### **SpaceX Data Collection.**

Request to the SpaceX API. <br>
Clean the requested data. 

#### <ul>[SpaceX Data Collection - Jupyter Notebook](https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/GH_jupyter-labs-spacex-data-collection-api_v5.ipynb)</ul>


### **Data Wrangling.**

In this lab, we will perform some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models.

#### <ul>[SpaceX Data Wrangling - Jupyter Notebook](https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/GH_labs-jupyter-spacex-Data%20wrangling_v3.ipynb)</ul>

### **Web scraping Falcon 9 and Falcon Heavy Launches Records from Wikipedia**

Web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled List of Falcon 9 and Falcon Heavy launches. Beautiful soup. 

#### <ul>[Falcon9 webscraping - Jupyter Notebook](https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/GH_jupyter-labs-webscraping_v4.ipynb)</ul>  
  
 
  
### **EDA - Undertanding Dataset. SQL Queries.**

Understand the Spacex DataSet <br>
Load the dataset into the corresponding table in a Db2 database. <br>
Execute SQL queries to answer assignment questions
  
#### <ul>[EDA - Undertanding Dataset - Jupyter Notebook](https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/GH_jupyter-labs-eda-sql-coursera_v10.ipynb)</ul>
  

### **EDA Data visualization**

EDA Data visualization. Exploring and Preparing Data.  <br> 
Perform exploratory Data Analysis and Feature Engineering using Pandas and Matplotlib Exploratory Data Analysis. <br>
Preparing Data Feature Engineering<br>
In this assignment, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is due to the fact that SpaceX can reuse the first stage.

#### <ul>[EDA - Data Visualization - Jupyter Notebook](https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/GH_jupyter-labs-eda-dataviz-v10.ipynb)</ul>

 
   
### **SpaceX Launch Records Dashboard**
Dashboard Application with Plotly Dash about SpaceX launch sites, sucess rate and payload. 
  In the previous exploratory data analysis labs, you have visualized the SpaceX launch dataset using matplotlib and seaborn and discovered some preliminary correlations between the launch site and success rates. 
- Launch Site Drop-down Input Component
- Callback function to render success-pie-chart based on selected site dropdown 
- Range Slider to Select Payload 
- Callback function to render the success-payload-scatter-chart scatter plot. 

Note: the interactive Notebook doesnot work on Github. Must be downloaded and executed locally. Or on Google Colab.

#### <ul>[Dashboard - Jupyter Notebook](https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/GH_Build_a_Dashboard_Application_with_Plotly_Dash_v10.ipynb) </ul>


### **Launch Sites Locations Analysis with Folium**
 
  Interactive 
The launch success rate may depend on many factors such as payload mass, orbit type, and so on. It may also depend on the location and proximities of a launch site, i.e., the initial position of rocket trajectories. Finding an optimal location for building a launch site certainly involves many factors and hopefully we could discover some of the factors by analyzing the existing launch site locations. <br>
In this lab, you will be performing more interactive visual analytics using Folium.<br>
Note: The interactive Notebook does not work on Github. It must be downloaded and run locally, with an Anaconda distribution for example. Or on Google Colab. 
  
#### <ul>[Launch sites - Interactive Notebook with Folium](https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/GH_lab_jupyter_launch_site_location_v4.ipynb)


### **SpaceX Launch Success. Machine Learning classification**

Machine Learning Prediction using Classification Algorithms: KNN, Decision Tree, SVM, Logistic Regression. <br>
Optimization of hyperparameters. 
  
#### <ul>[Machine Learning - Jupyter Notebook](https://github.com/DrStef/Applied_Data_Science_Capstone_SpaceX_IBM/blob/main/GH_SpaceX_Machine%20Learning%20Prediction_Part_5_v8_shuffling.ipynb)</ul>

<br>
<br>
<br>

Stephane D. Oct-2022
Rev. Dec-2022
 
