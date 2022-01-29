# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![image](https://github.com/icheung487/MechaCar_Statistical_Analysis/blob/main/Images/Summary.png)

From the above model summary we can see that: 
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
* The vehicle weight, spoiler_angle and AWD provide a non-random amount of variance to the mpg values.  All three have the lowest P-value. 
*
* Is the slope of the linear model considered to be zero? Why or why not?
This linear model indicates that the slope is NOT zero.  The reason why it is not zero is because the p-value (5.35e-11), is much smaller than the significance level of 0.05%. This shows that there is sufficient evidence to reject our null hypothesis. 

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
* The model shows a R-square value of a 0.7149, which equates to about 71% mpg predictions will be concluded by this model.  This is a high consideration that the model will predict mpg values correctly.  For these reasons, we can say we are 71% confident that this model can predict effectivelty. 


## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

![image](https://github.com/icheung487/MechaCar_Statistical_Analysis/blob/main/Images/total_summary.png)
## T-Tests on Suspension Coils
then briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

## Study Design: MechaCar vs Competition.
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?
