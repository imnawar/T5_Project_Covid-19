# Project 1 Proposal 


This repo is one of the T5 Bootcamp requirements. 


# There is any relation between weather and covid-19 cases?

Under the covid-19 pandemic conditions, and what increases the covid cases I going to introduce this study of covid-19 and the weather relation to discover if there is a relation between these two variables? 

Based on predictions of future weather, this will assist in forecasting future covid-19 cases. 

Getting better-protected ways for individuals with the days when covid levels predected are high is the benefit of this study.

## Dataset
To achieve the goal of this study the dataset **[NeurIPS 2020] Data Science for COVID-19 (DS4C)** will be used. 
This dataset can be found [here](https://www.kaggle.com/kimjihoo/coronavirusdataset) at Kaggle.

This dataset was released by KCDC (Korea Centers for Disease Control & Prevention). It contains multiple ```.csv``` files. 

Each weather sample cosist of these features: date, mean_avg_temp, mean_min_temp, mean_max_temp, mean_precipitation, mean_max_wind_speed, mean_most_wind_direction, mean_avg_relative_humidity, day, week. And the timpe sample consist of date, time, test, negative, confirmed, released and deceased. 

The data will be merged more than one ```.csv``` file for that the single sample is cosist of multiple features. 

The important features for this study are features such as **date, mean_avg_temp, mean_min_temp, mean_max_temp and the confirmed** all of which provide relevant information regarding this study. 

Due to the success of Machine Learning (ML) in identifying the correlation between the data, I will fit my data using ML and discover if there is a correlation between the weather and the COVID-19. 
Furthermore, Maybe I'll use a model that predicts how many confined cases will occur based on weather predictions over the next few days. if there is any correction between weather and covid. 

## Tools

There are tools that will be used to achieve the goal of this study, such as: ```sklearn, matplotlib, pandas``` for discovering the data and train a model for instance **Linear regression. The work will be done through Jupyter notebook.

## **TO DO**: 
- Explore the data and come up with EDA phases then use a ML model to fit the data.  
- **NOTE:** the used features may bey increased and the model as well. 