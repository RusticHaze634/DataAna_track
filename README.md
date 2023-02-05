# Shopping-Intention-Analysis

### a project: An Analysis and Prediction Project To find Consumers’ Purchasing Intention

- | [Click here for the code](https://github.com/RusticHaze634/Shopping-Intention-Analysis/blob/main/Shopper_Intention_1.ipynb) |  
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

 Details of Data Columns :
![image](https://user-images.githubusercontent.com/38161827/216852394-3ff19dfc-a60a-4a27-907a-daa81d3c61d9.png)
![image](https://user-images.githubusercontent.com/38161827/216852398-9fd792cd-48ae-4146-ac46-60966325c46d.png)


## 2. Work Flow-chart
![image](https://user-images.githubusercontent.com/38161827/216851062-26b22488-9845-4db2-9aa2-76cfa6d7a04e.png)


## 3. Platform and Tools Utilised in the Project
- Python coding and execution platform for the research work: **Google Colaboratory**
- Graph Plotting and Image Generation: **Matplotlib, Plotly**
- Data Preprocessing, Model Design: **TensorFlow Keras, Python**
- Project Visualistion: MS Powerpoint, MS PowerBi

## 4. Required Libraries 

For EDA, Visualisation & Preprocessing
- NumPy
- Pandas
- Pyplot  from Matplotlib 
- Seaborn  

Forr Data Sampling and Segmentation
- Scikit-Learn
- collections
- imblearn

For Predictive Model Designing, predction, Assessment
- Scikit-Learn

## 5. EDA & Visualisation

## 6 Dataset Segmentation
![image](https://user-images.githubusercontent.com/38161827/216852582-75ec8f18-b16d-489a-80ab-7733155af18e.png)


## 7. Dealing with Data Imbalance

- **Reason:** - Because the training data is an imbalanced dataset . It is skewed in the direction of the 'Not purchased' category. 
- **Step to take:**- We have to stratify our training data so that the ratio of training labels is equal. And this way we can avoid bias in prediction.

### Stratifying/ Imabalnce Handling
- stratified shuffle split package in Scikit

## 8. Model Design for Intention Classification and Best Model
- Naive Bayes Classifier
- Logistic Regression
- Support Vector Machine
- Random Forest   
- MLP Classifier
- Decision Tree

#### Training and Testing Accuracy Comparison of Different Models:
![image](https://user-images.githubusercontent.com/38161827/216852546-b1bbc8a7-e4db-4f40-a4f0-f0fcc75aef46.png)


To find the best model we have to consider the Underfitting-Overfitting concept.  
If both the training accuracy and test accuracy are close then the model has not overfit. If the training result is very good and the test result is poor then the model has overfitted. If the training accuracy and test accuracy is low then the model has underfit.

- Now, From above predictive models we see that the training accuracy (99.97%) for Decision Tree model is really high, but the testing accuracy is far low (84.67%)  
-- > So this is an overfitted model.

- The MLP model shows promising result wher the training accuracy (88.24%) and testing accuracy (87.26%) is not far away from each other.  
--> So this can be considered a good model.

- Similarly , Logistic regression model shows almost same result as the MLP one, with Training Accuracy of 88.21 % and a Testing Accuracy of 87.51%   
--> This is also a good one.

- Only in the case of Random Forest model, the training accuracy (90.58%) is close to its testing accuracy (89.49%). 
--> This one seems best fit model, till now.

## 9. Reasons for Choosing RF
- The training and testing accuracies are very close to each other, Less biasing probability in prediction
- Testing accuracy is higher than other model  - 89.49%.
- Precision, Recall, and F1-scores are higher than other tested models
- Precision for ‘True’ and ‘False’ both the cases are really high due to the data imbalance handling.
- An over-sampling approach (SMOTE) for imbalance handling was tested but did not improve the result.



