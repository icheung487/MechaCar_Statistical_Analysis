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

Above is the summary of all manufactoring lots.  The variance PSI is 62.29, which is less than the requirement of 100 pounds per square.  Overall, the population meets the PSI variance requirements as mentioned above. 

![image](https://github.com/icheung487/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.png)

However, when looking at the three lots individually they tell a different story.  Lot 1 and 2 have variance PSI of 0.98 and 7.47 respectively, which meets the variance requirement.  Lot 3 has a variance of over 150 which exceeds the weight requirement.  Lot 3 will need to be flagged since this does not meet the design specs. 

## T-Tests on Suspension Coils
then briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
Below is a screenshot of my t-test results. 

In the overall t-test results, we can see the mean is about 1490, which what we say in the above summary lots.  With the p-value of 0.06, which is slighly higher than the significance level, we can say at a high-level not to reject the null hypothesis.  However, as we look at each lot it tells a different story, similiar to the above when looking at the variance PSIs. 
    * Lot 1 and 2 both have about the same mean with a p-value above the significance level. This is clear that we would NOT reject the null hypothesis.
    * Lot 3 has a mean of 1496 and a p-value of 0.04.  The p-value is less than the significance level, which indicates to reject the null hypothesis.

![image](https://github.com/icheung487/MechaCar_Statistical_Analysis/blob/main/Images/t-test.png)

## Study Design: MechaCar vs Competition.
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:

What metric or metrics are you going to test?
Metrics that I would test: price, maintenance, gasoline efficiency, and safety rating

What is the null hypothesis or alternative hypothesis?
Null Hypothesis: MechaCar cars is the most cost effective among the other metric factors.
Alternative Hypothese: MechaCar cars  is not cost effective amount the other metric factors.

What statistical test would you use to test the hypothesis? And why?
Since I'm looking to test more than one independent variable, I would suggest performing the multiple linear regression model.  We would determine the coorelation between price vs. the other metrics (gasoline efficiency, maintenance, and safety rating).


What data is needed to run the statistical test?
Data set that is needed is MPG, safety rating, average selling price, and average maintenance cost.
