# Shopping-Intention-Analysis

### a project: An Analysis and Prediction Project To find Consumers’ Purchasing Intention

### | [Click here for the code](https://github.com/RusticHaze634/Shopping-Intention-Analysis/blob/main/Shopper_Intention_1.ipynb) |  
------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/RusticHaze634/Shopping-Intention-Analysis/blob/main/imageshopping.jpeg)

## Introduction
- Market opportunity has been generated due to the rise in e-commerce activity over the past several years.
- But low conversion rates mean that innovative approaches are needed to reach today's digital consumers with relevant offers. 
- An experienced salesperson at a physical or offline store can use their knowledge to provide consumers with individualised recommendations. Time efficiency, sales, and profits all benefit from this knowledge to varying degrees. 
- Companies in the fields of E-commerce and information technology spend a lot of money on early detection and behavioural prediction algorithms that attempt to mimic the actions of a human salesman in an online store. 
- Due to this trend, several academic research employing machine learning techniques have been proposed to investigate the issue from various vantage points. 
- Some studies focus on classifying visits based on the consumer's navigational patterns

## 1. Used Dataset:
### Online Shopper Intention Dataset
- The dataset consists of feature vectors belonging to 12,330 sessions.
- The data set is a set of 18 features: 10 numerical and 8 categorical.
- Dataset is split into 10,422 entries where the shoppers did not purchase and 1908 entries where the shoppers did purchase. 
- The dataset was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.

### 2. Work Flow-chart
![image](https://user-images.githubusercontent.com/38161827/216851062-26b22488-9845-4db2-9aa2-76cfa6d7a04e.png)

<a id="top"></a>
<div class="list-group" id="list-tab" role="tablist">
<h3 class="list-group-item list-group-item-action active" data-toggle="list" role="tab" aria-controls="home">  Table of Content</h3>
    
   * [Used Dataset](## 1.)
   * [Missing Value Handling](#2)
   * [Duplicate Rows Handling](#3)
   * [Renaming Columns](#4)
   * [Replace Null values](#24)
   * [Introduction of MONTH and Related Visualization ](#25)
   * [Exploratory Data Analysis](#5)
   * [Questions :](#6)
        * [1. Top 10 starting location](#7)
        * [2. Which was the most Frequent Starting Point?](#8)
        * [3. Top 10 STOP locations](#9)
        * [4. Which was the most Frequent Stopping Point?](#10)
        * [5. What is the number of trips per month?](#11)
        * [6. What is the number of trips per day? ](#12)
        * [7. How many trips for each purpose?](#13)
        * [8. How many trips in any particular day of all months (Category-wise) ?](#14)
        * [9. How many trips in any weekday?](#15)
        * [10. Is there any Round Trip? If, Yes, then How many Round Trips?](#16)
        * [11. Calculate Ride durations and Analyse](#17)
        * [12. Show Month-wise number of Uber Rides](#18)
        * [13. At which day uber rides were mostly used?](#19)
        * [14. Which was the Longest and the Shorest Ride Months (Based on Average Distance covered per month)?](#20)
        * [15. When was the Max no. of Trips in a day generally?](#21)
        * [16. Speed](#22)
   * [Save the Result](#23)

### 3. Platform and Tools Utilised in the Project
- Python coding and execution platform for the research work: **Google Colaboratory**
- Graph Plotting and Image Generation: **Matplotlib, Plotly**
- Data Preprocessing, Model Design: **TensorFlow Keras, Python**
- Project Visualistion: MS Powerpoint, MS PowerBi

### 4. Required Libraries 
