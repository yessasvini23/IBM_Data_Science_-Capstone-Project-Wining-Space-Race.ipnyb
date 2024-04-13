# IBM_Data_Science_-Capstone-Project-Wining-Space-Race.ipnyb


#Winning Space Race with Data Science

**IBM-Applied-Data-Science-Capstone-Project**

#Problem Statement:

SpaceX is successful because their rocket launches are relatively inexpensive. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upwards of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. Spaces X’s Falcon 9 launch like regular rockets. There are three stages of a rocket launch. The payload is enclosed in the fairings. Stage two, or the second stage, helps bring the payload to orbit, but most of the work is done by the first stage. This stage does most of the work and is much larger than the second stage. This stage is quite large and expensive. Unlike other rocket providers, SpaceX's Falcon 9 can recover the first stage. Sometimes the first stage does not land. Sometimes it will crash. Other times, Space X will sacrifice the first stage due to the mission parameters like payload, orbit, and customer.


In this project, you will take the role of a data scientist working for a new rocket company - Space Y that would like to compete with SpaceX founded by Billionaire industrialist Allon Musk. My job is to determine the price of each launch. I did this by gathering information about SpaceX and creating dashboards for the team. I also determined if SpaceX will reuse the first stage. Instead of using rocket science to determine if the first stage will land successfully, I trained a machine learning model and use public information to predict if SpaceX will reuse the first stage.


#Objective:

The objective is very clear. I have to evaluate the viability of the new company Space Y to compete with Space X.

#Desirable answers:

The best way to estimate the total cost for launches, by predicting successful landings of the first stage of rockets; and Where is the best place to make launches.

#Methodology :

1.Data Collection from 2 sources - i) SpaceX API & ii) Webscrapping from wikiepdia

2.Data Wrangling - Collected data was enriched by creating a landing outcome label based on outcome data after summarizing and analyzing features

3.EDA using SQL & Visualization

4.Interactive Visual Analysis by creating Dashboard

5. Machine Learning Predictive Analysis using Classification Models - Data that was collected until this step were normalized, divided in training and test data sets and evaluated by four different classification models (Logistic Regression, Support Vector Model, Decision Tree & K Nearest Neighbours Model), being the accuracy of each model evaluated using different combinations of parameters.


#Results:

* Space X uses 4 different launch sites;
* The first success landing outcome happened in 2015 fiver year after the first launch;
* Almost 100% of mission outcomes were successful;
* Two booster versions failed at landing in drone ships in 2015: F9 v1.1 B1012 and F9 v1.1 B1015;
* The number of landing outcomes became as better as years passed.
* Using interactive analytics was possible to identify that launch sites use to be in safety places, near sea and have a good logistic infrastructure around
*  Predictive Analysis showed that Decision Tree Classifier is the best model to predict successful landings, having accuracy over 87% and accuracy for test data 
    over 94%.













