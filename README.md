# Bike Sharing Demand Prediction Assignments
Given the dataset for Bike Sharing, this project builds a multiple linear regression model to predict the demand count of bike sharing based on multiple features that explain the targetted variable varience portion.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
### Objective
To build a linear regression model that predicts the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
### Steps followed for building the model
- Reading and Understanding the Data
- Visualising the Data
- Data Preparation
- Splitting the Data into Training and Test Data
- Building Linear Model
- Residual Analysis of Train Data
- Making the Predictions using Final Model
- Model Evaluation using Test Set

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Out of 16 feature variables given in the dataset, there are number of variables found to be insignificant and number of categorical variables were dummified for better model prediction capabilities
- As a results of all the steps followed to build the multiple linear regression model, following conclusions were made on the model
  - 𝑅−𝑆𝑞𝑢𝑎𝑟𝑒𝑑 𝑆𝑐𝑜𝑟𝑒𝑜𝑛 𝑇𝑒𝑠𝑡 𝑆𝑒𝑡 = 0.7842
  - 𝑅−𝑆𝑞𝑢𝑎𝑟𝑒𝑑 𝑆𝑐𝑜𝑟𝑒𝑜𝑛 𝑇𝑟𝑎𝑖𝑛 𝑆𝑒𝑡 = 0.8260
  - Final Linear regression equation for best fitted line
    𝑐𝑛𝑡=0.0706+0.2320×𝑦𝑟+0.0559×𝑤𝑜𝑟𝑘𝑖𝑛𝑔𝑑𝑎𝑦−0.1658×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑−0.0788×𝑤𝑒𝑎𝑡ℎ𝑒𝑟𝑠𝑖𝑡2−0.2814×𝑤𝑒𝑎𝑡ℎ𝑒𝑟𝑠𝑖𝑡3+0.0677×𝑤𝑒𝑒𝑘𝑑𝑎𝑦6+0.0283×𝑤𝑒𝑒𝑘3+0.0750×𝑠𝑢𝑚𝑚𝑒𝑟+0.1289×𝑤𝑖𝑛𝑡𝑒𝑟

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
### Language and Library Used
#### Language
* Python v3.11.5
#### Numerical Analysis and Data Analysis
* Numpy v1.24.3
* Pandas v2.0.3
#### Data Visualization
* Seaborn v0.12.2
* MatplotLib-pyplot v3.7.2
#### Model Builders
* SKLearn v1.3.0
* Statsmodels v 0.14.0

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@anantjs11] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
