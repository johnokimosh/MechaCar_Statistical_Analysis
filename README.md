# Statistics and R

# Overview of Project
This assignment consists of three technical analysis deliverables and a proposal for further statistical study. You’ll submit the following:

- Deliverable 1: Linear Regression to Predict MPG
- Deliverable 2: Summary Statistics on Suspension Coils
- Deliverable 3: T-Test on Suspension Coils
- Deliverable 4: Design a Study Comparing the MechaCar to the Competition

## Linear Regression to Predict MPG
- ![1-1 - LM](https://user-images.githubusercontent.com/27740513/147894725-299617ec-6b4e-4e54-90b5-1f09eb047590.png)

- ![1-2 - Summary](https://user-images.githubusercontent.com/27740513/147894702-6a884ad8-1ecf-437c-9fe9-9559111aeadb.png)

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- vehicle length and ground clearance have a non-random amount of variance to the mpg values. These p-values are close to zero and provide no signifigant variation to mpg values.
### Is the slope of the linear model considered to be zero? Why or why not?
The slope is near zero. Vehicle length and ground clearance may be skewing the data. Additional analysis could be done by omitting these data points.
### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This current model does not predict mpg effectively. Remodeling with analysis of weight, spoiler angle and AWD could provide better analysis.
## Summary Statistics on Suspension Coils
- ![2-1 - summarize](https://user-images.githubusercontent.com/27740513/147895513-9293258d-88fb-4ff4-ae5b-7131053ced0c.png)

- ![2-2 - grouby](https://user-images.githubusercontent.com/27740513/147895520-9e577b7f-dd4b-4a47-aff3-bdf2c2935c8a.png)

- Q: The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- A: Current manufacturing data DOES NOT meet 100 ppsi variance. Variance in Lot1 and Lot2 meet specifications. Lot3 variance is not meeting designing specifications. Variance is 170 ppsi with a standard deviation of 13. 
-

## T-Test on Suspension Coils
- ![3-1 - ttest](https://user-images.githubusercontent.com/27740513/147898137-82e1dda8-7657-433e-89ee-793e4f9b78f5.png)

- ![3-2 - subsets](https://user-images.githubusercontent.com/27740513/147898141-58e6da3a-7b08-4292-8d71-4e9184cbce47.png)

### briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
- When using a samlple of the entire population variance is significant due to the inclusion of samples from Lot 3 which does not meet manufacturing variance levels. When conducting an analysis using a subsets of samples from each specific lot, the variance is near zero for Lot 1 and Lot 2, and significant variance with Lot 3.

## Study Design: MechaCar vs Competition

### Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

### What metric or metrics are you going to test?
- With the current data sets, MechaCar can compare its MPG performance of vehicle models to MPG performance from other manufacturers. Also, comparisons of suspension coil manufacturing tolerances could be made with other manufacturers. Outside of the current data sets, the comparisons could be endless, manufacturing costs is a good example of a potential comparison.
### What is the null hypothesis or alternative hypothesis?
- Measurements from various stages of the manufacturing process would need to be collected and comparable data from various manufacturers should be considered. Does the data measured correlate to the a savings in manufacturing costs for MechaCar and are these measures different or similar when compared to other manufacturers.
### What statistical test would you use to test the hypothesis? And why?
- Chi-Squared would be the recommended test when comparing manufacturing costs between different groups of manufacturers.
### What data is needed to run the statistical test?
- Manufacturing costs from MechaCar and other comparable automobile manufacturers. Specifially costs from a variety of stages of the manufacturing process.
