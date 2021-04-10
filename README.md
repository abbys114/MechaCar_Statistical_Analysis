# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![Alt Text](https://github.com/abbys114/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202021-04-08%20at%2012.54.36%20PM.png)

The variables that provide a non-random amount of variance to the mpg values in the dataset are vehicle weight, spoiler angle, and AWD.  The slope in this model is not zero because R-squared does not equal zero, which would mean there was no correlation.  In this case, the adjusted R-squared value equals .6825, meaning there is a moderate positive correlation.  This linear model is helpful with estimating mpg of MechaCar prototypes, but should be further looked into to find a better model with possible other factors.

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Is the slope of the linear model considered to be zero? Why or why not?
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?


## Summary Statistics on Suspension Coils
![Alt Text](https://github.com/abbys114/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202021-04-09%20at%209.48.28%20PM.png)
![Alt Text](https://github.com/abbys114/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202021-04-09%20at%209.06.15%20PM.png)

The design specifications for the MechaCar suspension coils of not exceeding 100 pounds per squae inch are met for all manufacturing lots in total, but not individually.  As seen in the image above, Lot 3 does not meet this qualification.  

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

## T-Tests on Suspension Coils
![Alt Text](https://github.com/abbys114/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202021-04-09%20at%2010.18.15%20PM.png)
![Alt Text](https://github.com/abbys114/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202021-04-09%20at%2010.18.54%20PM.png)

The t-test results show that we should reject the null hypothesis for Lot 1 and 2, but keep the null hypothesis for Lot 3. Since the p-value is greater then .05, we can reject the null hypothesis for Lot 1 and 2.  This means that the weight capacities of the suspension coils are not consistent between all the lots.

summarize your interpretation and findings for the t-test results

## Study Design: MechaCar vs Competition
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?

Using statistics, we can compare MechaCar against the competition.  For our study, we are going to compare cost, fuel efficiency, and safety ratings. The cost will be compared in dollars, the fuel efficiency will be measured in miles per gallons, and the safety rating will be a rating out of five stars.  In this study, our null hypothesis wii be that cost, fuel efficiency, and safety ratings are the same between MechaCar and its competition.  We would use a T-test to compare the cost and fuel efficency amongst the competitors and a chi-square test to compare safety ratings becasue it is categorical data.  For running the statistical test, we will need data  on cost, fuel efficiency, and safety ratings for MechaCar and its competitors.
