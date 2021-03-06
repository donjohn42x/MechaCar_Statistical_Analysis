# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![Screenshot (55)](https://user-images.githubusercontent.com/82130746/160244326-58905811-33b7-4291-813d-61fe26e02e5d.png)

Based on the results of the regression analysis on the 5 variables in relation to MPG, we can determine which factors contribute to MPG at a given significance level. If we choose a level of significance of 0.05, then we can coclude that vehicle length, vehicle length, and ground clearance contribute to the MPG on a car (Based on the p-values shown in the analysis)

## Summary Statistics on Suspension Coils
![Screenshot (60)](https://user-images.githubusercontent.com/82130746/160244337-8bda2f3a-befe-4536-b8be-636e8219b561.png)
![Screenshot (59)](https://user-images.githubusercontent.com/82130746/160244331-d71615d8-f0c4-4bd2-b749-fa4889d29a7a.png)

Based on the output of these tables, we can see that the data may meet the design specifications for all manufacturing lots in total, but does not meet design specifications for each indivdual lot given that the specifications dictacte that the variance of the suspension coils must not exceed 100. Looking at the table containing the statistics the entire dataset, we can see that the variance is 62.29, but if we are to look at the table with the individual lots we can then see that lot3 has a variance of 170.29.

## T-Tests on Suspension Coils
![Screenshot (56)](https://user-images.githubusercontent.com/82130746/160244328-59fc16b1-d672-41a4-84bf-5a00a1d4d15d.png)
![Screenshot (57)](https://user-images.githubusercontent.com/82130746/160244330-6ccc9985-aaf9-4ac3-a163-684416eb6b2d.png)

At a level of significance of 5%, we cannot conclude that the average PSI is significantly different from 1500. The first t-test that is shown results in a p-value of 0.06 which is just above of significance level and so we cannot reject the null hypothesis of this test at this level. If we are to look at the lots individually, the the only lot that we can conclude has an average PSI different from 1500 is lot 3 based on the fact that the p-value of 0.04 allows us to reject the null hypothesis at our level of significance of 0.05. 

## Study Design: MechaCar vs Competition
To quantify how the MechaCar performs against the competition, we can create a study that takes the MPG, horse power, maintanance cost, and safety rating of MechaCars and competitor cars to compare these aspects between MechaCars and the competition. We can do so by conducting individual paired t-tests on these factors with the null hypothesis being that the factors are the same. In doing so, we may be able to see how these aspects differ between MechaCars and competitor cars. 
