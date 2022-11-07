# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Del1_linreg](https://user-images.githubusercontent.com/106286533/189547872-e367e718-7294-4416-b718-0b7df2f0351d.png)
![Del1_summstats](https://user-images.githubusercontent.com/106286533/189547884-664d3b97-0563-4f9d-9596-802b555f6870.png)

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
•	Vehicle length, Vehicle Weight and Ground Clearance gave a non random amount of variance because their p-values were less than .05 therefore statistically significant.
### Is the slope of the linear model considered to be zero? Why or why not?
•	No the slope is not zero because all of the variables are greater than or less than zero.
### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
•	The model predicts MPG of the MechaCar at a 72% effective rate as the multiple R-squared value is 0.7149. 

## Summary Statistics on Suspension Coils

![lot_summary_df](https://user-images.githubusercontent.com/106286533/189547901-360fd32f-1d7e-4c0d-b6d9-02e075992694.png)
![total_summary_df](https://user-images.githubusercontent.com/106286533/189547913-eb8b88e0-585b-4573-b1a3-566ab2a3e94f.png)

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
•	The overall variance is 62 which meets design specifications.  However, when reviewing the lot summary data, Lot 3 has a variance of 170.29 which is well above the requirement of 100 PSI and does not meet the design requirements.  This variance is significantly higher than the other 2 lots which have variances of 1 and 7 respectively.

## T-Tests on Suspension Coils

![ttest_allLots](https://user-images.githubusercontent.com/106286533/189547927-a52547ca-496a-4f11-8381-f2cf0598e58c.png)
![ttest_Lot1](https://user-images.githubusercontent.com/106286533/189547939-d384bb20-06fa-4c98-819a-1bb2a933166f.png)
![ttest_Lot2](https://user-images.githubusercontent.com/106286533/189547945-dbacba3e-10f5-4bf0-95cf-e49c909eb0de.png)
![ttest_Lot3](https://user-images.githubusercontent.com/106286533/189547953-eca5ed4c-bbe2-41e9-afdc-52444c14f3c4.png)

### Lot 3 had the largest confidence interval spanning from 1492.43 – 1499.85 showing that there are inconsistencies in the manufacturing within that lot.  Lot 3 also had the lowest p-value at 0.042.  The mean for Lot 1 and Lot 2 were at 1500 and 1500.2 respectively, but Lot 3 was 1496.14 which brought the population mean down to 1498.78.

## Study Design: MechaCar vs Competition
### There are other metrics I would recommend looking at in order to determine how well MechaCar performs against the competition.  First, I would look at maintenance and repair costs for wear and tear parts.  This would include oil changes, brake, rotor, and tire replacements, etc.  The data should contain cost and interval of change.  These could be summarized to determine an average yearly maintenance cost.  Other metrics could include safety rating, difference in city/highway fuel efficiency as well as overall cost of the vehicle.  An ANOVA test would be able to test the categorical data show the statistical differences from multiple samples.  The Pearson Correlation Coefficient can also be used to see how the different categories affect each other.  These tests can compare samples from the MechaCar data and data for other cars in its same class.  If the significance level is 0.05 or higher, then the MechaCar has the same or similar performance in these categories as the competition.  If the significance level is lower than 0.05, then the MechaCar is performing significantly different than the competition in these categories.    
