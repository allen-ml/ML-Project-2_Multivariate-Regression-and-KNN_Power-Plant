# Project 2: Power Plant - Multivariate Regression

*Combined Cycle Power Plant Data Set*

Coding was done in Google Colab and results are presented here.

The dataset contains data points collected from a Combined Cycle Power Plant over  6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (PE) of the plant. 

**1. Download the Combined Cycle Power Plant data1 from:**
https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant 

**2. Data Exploration**
![P2_Data_Exploration_Graph.png](./assets/P2_Data_Exploration_Graph.png)
![P2_Data_Exploration_Table.PNG](./assets/P2_Data_Exploration_Table.PNG)


**3. Initial Linear Regression on all data - Without removing insignificant features**
![P2_Linear_Regression_Graph_1.png](./assets/P2_Linear_Regression_Graph_1.png)

**4. Multi-Variat Regression after removing insignificant terms**
![P2_Multi_Var_Linear_Regression_Graph_2.PNG](./assets/P2_Multi_Var_Linear_Regression_Graph_2.PNG)

**5.  Full linear regression model with all pairwise interaction terms and states whether any interaction terms are statistically signifcant or not**
![P2_Full_Linear_Regression_Graph_3.PNG](./assets/P2_Full_Linear_Regression_Graph_3.PNG)

**6. Test the significance of the states statistically**
![P2_Regression_Stats_Graph_4.PNG](./assets/P2_Regression_Stats_Graph_4.PNG)
![P2_Regression_Stats_Graph_5.PNG](./assets/P2_Regression_Stats_Graph_5.PNG)

**7. Eliminate insignificant terms and check the statistics of the remianing - P-Value, R-squared and Adj. R-squared:**
![P2_Regression_Stats_Graph_6.PNG](./assets/P2_Regression_Stats_Graph_6.PNG)

**8. Train the regression model on a randomly selected 70% subset of the data with all predictors. Test both models on the remaining points and report your train and test MSEs.**
![P2_Regression_Stats_Graph_7.PNG](./assets/P2_Regression_Stats_Graph_7.PNG)

**9.  k-nearest neighbor regression using both normalized and raw features. Found the value of k: 1,2, ...,100 that gives the best fit. Plotted the train and test errors in terms of 1/k.**
![P2_Regression_Stats_Graph_8.PNG](./assets/P2_Regression_Stats_Graph_8.PNG)
