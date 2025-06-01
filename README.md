# Relationship between obesity and behavioral health features - a multi-class classification model to detect obesity based on survey data

This project studies the relationship between different lifestyle habits and behaviors, and obesity. For this purpose, I have analyzed the obesity dataset from UC Irvine Machine Learning Repository that has data on obesity levels in individuals from Mexico, Peru and Colombia, along with their eating habits and physical conditions. The dataset can be accessed here: ![Estimation of Obesity Levels](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition).

The response variable Obesity Level is a multi-class categorical variable with seven levels: Insufficient Weight, Normal Weight, Overweight I, Overweight II, Obesity I, Obesity II and Obesity III, in the order of progressively increasing Body Mass Index (BMI). The task at hand is to predict these classes based on feature variables in the data. This is a multinomial classification problem. For this purpose, I have applied and studied the performance of Random Forest and Boosting techniques combined with feature selection to find a final robust and high performing classifier. 

In this repository, I have two sections - Exploratory Data Analysis and Models. As the name suggests, Exploratory Data Analysis analyzes the relationship between obesity levels and different features. Based on important features identified, we then compare and evaluate the two classification techniques in the Model section.

## Exploratory Data Analysis

The number of records across each category are fairly similar, showing that there is no class imbalance issue.

<p align="center">
<img width="350" alt="image" src="https://github.com/user-attachments/assets/08482a26-e50a-4b72-908d-a301d2b9d953" />
</p>



<p align="center">
  <img src="Images/Obesity by age.png" alt="Chart" width="500"/>
</p>



<p align="center">
  <img src="Images/Physical Activity and obesity.png" alt="Chart" width="500"/>
</p>

