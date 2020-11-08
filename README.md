# MechaCar_Statistical_Analysis-

## Linear Regression to Predict MPG
The variables/coefficients that provided a non-random amount of variance to the mpg values in the dataset are the vehicle weights. Since the multiple R-squared is .7149 and the p-value is 5.35e-11, the slope of our linear model is zero. Since our R value is greater than our p-value. Therefore, we can fail to reject our null hypthesis. The linear model does predict our mpg of MechaCar protytpes effectively because 

![image]

## Summary Statistics on Suspension
Since the suspension coils variance must not exceed 100 pounds per square inch the current manufacturing data for all lots in total does meet the dsign specification. The variance for all the lots combined is 62.29356.

![image]

When looking at the indvidual manufacturing lots, Lot 1 and 2 variance is less than 100 but lot 3 is at 170. Therefore, lot 3 does not meet this design specification.

![image]

## T-Tests on Suspenion Coils
The results for T-Test for the suspenion coil across all manufacturing lots, one would fail to reject the null hypoethsis since the p-value is greater than .05. The average suspension coil is at 1498.78. 

![image]

When comparing lot 1 to lot 2 suspension coils the p-value is .6052. This means that we would fail to reject the null and this indicates that there is no statistcal difference between lot 1 and lot 2.

![image}

When comparing lot 2 to 3 , the p-value is .04199. This means that we would reject the null and that there are differences between the two lots.

![image]

When comparing lot 1 to 3 , the p-value is .04347. This means that we would reject the null and that there are differences between the two lots.

1[image]

## Study Design: MechaCar vs Competition

One of the metrics that can be tested to display MechaCar's performance against the competition would be to compare the city or highway fuel efficiency. The null hypothesis is that there would be no differences between MechaCar and the competition when comparing the city or highway fuel efficiency. The alternative would be that there would be differences. One statistical test that could be perofrmed to test the hypoethsis would be two sample t test because we would be comparing 2 sets of data from 2 different populations. The data we would need would be the city or highway fuel efficiency of MechaCar and one of the competitors. 
