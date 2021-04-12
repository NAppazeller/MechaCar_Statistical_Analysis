# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![](https://github.com/NAppazeller/MechaCar_Statistical_Analysis/blob/main/linear%20regression%20summary.jpg)

*Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?*

Vehicle weight, spoiler angle and all-wheel drive provided non-random amounts of variance.

*Is the slope of the linear model considered to be zero? Why or why not?*

The p-value of our linear regression analysis is 5.35 x 10<sup>-11</sup> , which is much smaller than our assumed significance level of 0.05%. There is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.

*Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?*

Yes, this linear model predicts the mpg of MechaCar prototypes effectively. Looking at the R-squared value of 0.7149 we can estimate an accurate prediction rate of 71%.   

## Summary Statistics on Suspension Coils

*The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?*

Lots 1 & 2 have a PSI variance of 0.98 and 7.47, respectively. Whereas Lot 3 has a PSI variance of 170.29 which does not meet current design specifications.

## T-Tests on Suspension Coils
### T-Test Across All Manufacturing
![](https://github.com/NAppazeller/MechaCar_Statistical_Analysis/blob/main/PTest%20Output_1.jpg)

### T-Tests Across 3 Manufacturing Lots
![](https://github.com/NAppazeller/MechaCar_Statistical_Analysis/blob/main/PTest%20Output.jpg)

Using t-tests we're able determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch. By observing the p-value we can see that the population lot and lots 1 & 2 have a p-value greater than 0.05% which indicates they are statistically different from the population mean of 1,500 pounds per square inch.

## Study Design: MechaCar vs Competition

In today's market, where many consumers have been significantly impacted by the Covid-19 pandemic, costs associated with vehicle ownership will be critical. Metrics that will need to be tested include the car's cost, fuel efficiency, and maintenance.

The alternative hypothesis would be how does MechaCar differentiate in car cost, mpg and maintenance from the competition.

Using competitor data related to car cost, fuel efficiency and maintenance we would perform t-tests.




