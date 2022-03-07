# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
The results for the linear regression were as follows:

![image](https://user-images.githubusercontent.com/92831138/156824679-e065369f-118c-433a-90ee-e9956877f3c8.png)

As can be seens, the angle of the spoiler and the presence of All Wheel Drive provide a non-random amount of variance to the Miles Per Gallon values in the dataset. The weight of the vehicle also provides a non-random amount of variance, albeit less than the prior two variables. The p value returned for the intercept indicated that the null hypothesis can be rejected as the slope is not considered to be zero. The R-Squared value indicates that the linear model will predict the mpg of the prototypes with relative effectiness. As it stands with the current data the model can predict with rouoghly seventy percent accuracy. 

## Summary Statistics on Suspension Coils
The results for the total summary and lot summary respectively are as follows:

![image](https://user-images.githubusercontent.com/92831138/156826623-b81212fc-af5a-4540-8e76-928fecc7f1b8.png)

![image](https://user-images.githubusercontent.com/92831138/156826654-a8b6c15e-3823-4ce3-beed-fb4e6e53faf4.png)

The current design specifications dictate that the variance of suspension coils must not exceed 100 pounds per square inch. The total summary for the three lots combined would meet the specifications with a variance of ~62.3, but the individual lot summaries indicate that grouping the results by lot tells a different story. The variances for Lot 1 and Lot 2 are both very minor, with the variance for Lot 1 being smaller than one. Comparatively, Lot 3 has a variance of 170, close to two times the specification's limitation.

## T-Tests on Suspension Coils
The t-test results for all lots, lot 1, lot 2, and lot 3 respectively are as follows:

![image](https://user-images.githubusercontent.com/92831138/157057384-1338298b-6cbd-43c0-b02d-9d3a9eb45332.png)

With the established significance level of 0.05 the t-test for all lots together has a p value that is slightly higher and indicates a statistically similar mean. 

![image](https://user-images.githubusercontent.com/92831138/157057429-78694b31-19b2-4574-8408-0502e8778679.png)

Lot 1 has a p value of 1 and has a statistically similar mean to the population mean used in the t-test.

![image](https://user-images.githubusercontent.com/92831138/157057479-d7214877-b8da-447a-9b00-fa138966d0f9.png)

Lot 2 has a p value 0.6 and, while less than lot 1, also has a statistically similar mean to the population mean used in the t-test.

![image](https://user-images.githubusercontent.com/92831138/157057524-124208b2-55a3-45ba-bc33-f6e02d4490f5.png)

Lot 3 has a p value of 0.04, below the established significance level of 0.05, indicating a mean that is not statistically similar to the population mean. This, combined with the summary statistics from the prior section, establishes that production in lot 3 has issues that should be resolved to bring it more in line with the other two lots.

## Study Design: MechaCar vs Competition

