# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![](https://github.com/NAppazeller/MechaCar_Statistical_Analysis/blob/main/linear%20regression%20output.jpg)

*Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?*

Vehicle weight, spoiler angle and all-wheel drive provided non-random amounts of variance.

*Is the slope of the linear model considered to be zero? Why or why not?*

The p-value of our linear regression analysis is 5.35 x 10<sup>-11</sup> , which is much smaller than our assumed significance level of 0.05%. There is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.

*Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Yes, this linear model predicts the mpg of MechaCar prototypes effectively. Looking at the R-squared value of 0.7149 we can estimate an accurate prediction rate of 71%.   

## Summary Statistics on Suspension Coils

*There is a summary that addresses the design specification requirement for all the manufacturing lots and each lot individually*

The suspension coil’s PSI continuous variable across all manufacturing lots
The following PSI metrics for each lot: mean, median, variance, and standard deviation.

detail and interpret the suspension coil summary statistics.

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?


## T-Tests on Suspension Coils
### T-Test Across All Manufactoring
![](https://github.com/NAppazeller/MechaCar_Statistical_Analysis/blob/main/PTest%20Output_1.jpg)

### T-Tests Across 3 Manufactoring Lots
![](https://github.com/NAppazeller/MechaCar_Statistical_Analysis/blob/main/PTest%20Output.jpg)

*There is a summary of the t-test results across all manufacturing lots and for each lot*
briefly summarize your interpretation and findings for the t-test results. 


## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?



