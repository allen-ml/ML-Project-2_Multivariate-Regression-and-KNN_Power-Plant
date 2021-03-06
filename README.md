# Project 2: Multivariate Regression and K-Nearest Neighbor
## Power Plant Energy Output

*Combined Cycle Power Plant Data Set*

Coding was done in Python in **Google Colab** and results are presented here.

The dataset contains data points collected from a Combined Cycle Power Plant over  6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (PE) of the plant. 

## Data Exploration ##

<!-- <img align="center" src="./assets/P2_Data_Exploration_Graph.png">-->
<p align="center">
  <img src="./assets/P2_Data_Exploration_Graph.png">
</p>

<p align="center">
  <img src="./assets/P2_Data_Exploration_Table.PNG">
</p>
<!--<img align="center" src="./assets/P2_Data_Exploration_Table.PNG">
<!-- ![P2_Data_Exploration_Graph.png](./assets/P2_Data_Exploration_Graph.png)-->
<!-- ![P2_Data_Exploration_Table.PNG](./assets/P2_Data_Exploration_Table.PNG) -->

## Regression Training
#### Train the regression model on a randomly selected 70% subset of the data with all predictors.

## Regression Testing
#### Test both models on the remaining points and report your train and test MSEs.

<p align="center">
  <img src="./assets/P2_Regression_Stats_Graph_7.PNG">
</p>

<!-- ![P2_Regression_Stats_Graph_7.PNG](./assets/P2_Regression_Stats_Graph_7.PNG)-->

## K-Nearest Neighbor Results
#### k-nearest neighbor regression using both normalized and raw features. Found the value of k: 1,2, ...,100 that gives the best fit. Plotted the train and test errors in terms of 1/k.

<p align="center">
  <img src="./assets/P2_Regression_Stats_Graph_8.PNG">
</p>

<!-- ![P2_Regression_Stats_Graph_8.PNG](./assets/P2_Regression_Stats_Graph_8.PNG)-->

## Analysis Details

**1. Download the Combined Cycle Power Plant data1 from:**


https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant 

**2. Initial Linear Regression on all data - Without removing insignificant features**


<p align="center">
  <img src="./assets/P2_Linear_Regression_Graph_1.png">
</p>

<!--![P2_Linear_Regression_Graph_1.png](./assets/P2_Linear_Regression_Graph_1.png)-->

**3. Multi-Variat Regression after removing insignificant terms**


<p align="center">
  <img src="./assets/P2_Multi_Var_Linear_Regression_Graph_2.PNG">
</p>
<!--![P2_Multi_Var_Linear_Regression_Graph_2.PNG](./assets/P2_Multi_Var_Linear_Regression_Graph_2.PNG)-->

**4.  Full linear regression model with all pairwise interaction terms and states whether any interaction terms are statistically signifcant or not**


<p align="center">
  <img src="./assets/P2_Full_Linear_Regression_Graph_3.PNG">
</p>

<!--![P2_Full_Linear_Regression_Graph_3.PNG](./assets/P2_Full_Linear_Regression_Graph_3.PNG)-->

**5. Test the significance of the states statistically**

<p align="center">
  <img src="./assets/P2_Regression_Stats_Graph_4.PNG">
</p>

<p align="center">
  <img src="./assets/P2_Regression_Stats_Graph_5.PNG">
</p>

<!--![P2_Regression_Stats_Graph_4.PNG](./assets/P2_Regression_Stats_Graph_4.PNG)-->
<!--![P2_Regression_Stats_Graph_5.PNG](./assets/P2_Regression_Stats_Graph_5.PNG)-->

**6. Eliminate insignificant terms and check the statistics of the remianing - P-Value, R-squared and Adj. R-squared:**

<p align="center">
  <img src="./assets/P2_Regression_Stats_Graph_6.PNG">
</p>

<!--![P2_Regression_Stats_Graph_6.PNG](./assets/P2_Regression_Stats_Graph_6.PNG)-->

**7. Training: Train the regression model on a randomly selected 70% subset of the data with all predictors.**
**Testing: Test both models on the remaining points and report your train and test MSEs.**

<p align="center">
  <img src="./assets/P2_Regression_Stats_Graph_7.PNG">
</p>

<!-- ![P2_Regression_Stats_Graph_7.PNG](./assets/P2_Regression_Stats_Graph_7.PNG)-->

**8. Results: k-nearest neighbor regression using both normalized and raw features. Found the value of k: 1,2, ...,100 that gives the best fit. Plotted the train and test errors in terms of 1/k.**

<p align="center">
  <img src="./assets/P2_Regression_Stats_Graph_8.PNG">
</p>
<!--![P2_Regression_Stats_Graph_8.PNG](./assets/P2_Regression_Stats_Graph_8.PNG)-->
