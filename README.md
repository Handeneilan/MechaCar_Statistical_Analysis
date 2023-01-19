# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

##### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle_length and ground_clearance.

##### Is the slope of the linear model considered to be zero? Why or why not?

Because of our P-value, we can assume that the slope is non zero.

##### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

R-squared is .7149, means there is a strong correlation for the dataset. ?f we only consider the R-squared, we can say data set is an effective data set. However there might be other variables, that affect the effectivenes of data set.

## Summary Statistics on Suspension Coils

#### Total Summmary

#### Lot Summary

When we look at the total summary variance is 62. Variance being smaler than 100 is good however if we look at the lot summary we see that the variance of lot3 is significantly higher than 100. That means Lot3 does not meet the design specifications.

## T-Tests on Suspension Coils

#### T-test for all lots

#### T-test for Lot1

#### T-test for Lot2

#### T-test for Lot3

It looks like Lot1 and Lot 2 show a normak distrubiton so we cannot really reject the null hypothesis.

## MechaCar vs Competition

When it comes to compairing there should be cost, car color, city fuel efficiency, highway fuel efficiency, horsepower, maintenance cost, or safety rating included as other metrics. 


##### What metric or metrics are you going to test?

Next step we should be testing the new metrics we mentioned above such as cost, car color, city fuel efficiency, highway fuel efficiency, horsepower, maintenance cost, or safety rating

##### What is the null hypothesis or alternative hypothesis?

Ho: There is no statistical difference between the competition's mpg dataset and MechaCar's mpg dataset.

Ha: There is a statistical difference between the competition's mpg dataset and MechaCar's mpg dataset.

##### What statistical test would you use to test the hypothesis? And why?

I think I would use a multiple linear regression to be able to see the correlation.

##### What data is needed to run the statistical test?

We would need the all data of MechaCar to be able to see the all kind of correlation that we want to learn. If we have some data of the competitors, that would be very helpful too.
