# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Alt Text](https://github.com/abbys114/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202021-04-08%20at%2012.54.36%20PM.png)

The variables that provide a non-random amount of variance to the mpg values in the dataset are vehicle weight, spoiler angle, and AWD.  The slope in this model is not zero because R-squared does not equal zero, which would mean there was no correlation.  In this case, the adjusted R-squared value equals .6825, meaning there is a moderate positive correlation.  This linear model is helpful with estimating mpg of MechaCar prototypes, but should be further looked into to find a better model with possible other factors.

## Summary Statistics on Suspension Coils

![Alt Text](https://github.com/abbys114/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202021-04-09%20at%209.48.28%20PM.png)
![Alt Text](https://github.com/abbys114/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202021-04-09%20at%209.06.15%20PM.png)

The design specifications for the MechaCar suspension coils of not exceeding 100 pounds per square inch are met for all manufacturing lots in total, but not individually.  As seen in the image above, Lot 3 does not meet this qualification.  

## T-Tests on Suspension Coils

![Alt Text](https://github.com/abbys114/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202021-04-09%20at%2010.18.15%20PM.png)
![Alt Text](https://github.com/abbys114/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202021-04-09%20at%2010.18.54%20PM.png)

The t-test results show that we should reject the null hypothesis for Lot 1 and 2, but keep the null hypothesis for Lot 3. Since the p-value is greater then .05, we can reject the null hypothesis for Lot 1 and 2.  This means that the weight capacities of the suspension coils are not consistent between all the lots.


## Study Design: MechaCar vs Competition

Using statistics, we can compare MechaCar against the competition.  For our study, we are going to compare cost, fuel efficiency, and safety ratings. The cost will be compared in dollars, the fuel efficiency will be measured in miles per gallons, and the safety rating will be a rating out of five stars.  In this study, our null hypothesis wii be that cost, fuel efficiency, and safety ratings are the same between MechaCar and its competition.  We would use a T-test to compare the cost and fuel efficency amongst the competitors and a chi-square test to compare safety ratings becasue it is categorical data.  For running the statistical test, we will need data  on cost, fuel efficiency, and safety ratings for MechaCar and its competitors.
