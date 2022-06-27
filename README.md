# MechaCar_Statistical_Analysis
In this analysis we will perform the following in an attempt to understand production troubles that are blocking the manufacturing team’s progress to alleviate the suffering:
* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.



## Linear Regression to Predict MGP

> Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The p value is very small, smaller than the .05 that shows significance. 

> Is the slope of the linear model considered to be zero? Why or why not?

There is then sufficient evidence to reject our null hypothesis which means that the slope of our linear model is not 0.

> Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

This linear model with a very low p score does mean that it is an accurate predictor of mpg in MechaCar prototypes.
<img width="642" alt="Screen Shot 2022-06-27 at 11 53 48 AM" src="https://user-images.githubusercontent.com/95602006/175994632-2a81b53b-2d1a-4db4-a6e9-a314cdaabeb1.png">


## Summary Statistics on Suspension Coils
> Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The variance increases pretty significantly from Lot 1 to Lot 2, and then from Lot 2 to Lot 3. With that being said, Lot 1 & 2 still meet the parameters for significance while the 3rd Lot does not.
![manufacturing-lot-summary](https://user-images.githubusercontent.com/95602006/175994398-5e12f5a0-3b5c-472e-a4fc-405686920263.png)


## T-Tests on Suspension Coils

## Study Design: MechaCar vs Competition
A statistical study that can quantity MechaCars ability to perform against competition:

> What metric or metrics are you going to test?

> What is the null hypothesis or alternative hypothesis?

> What statistical test would you use to test the hypothesis? And why?

> What data is needed to run the statistical test?
