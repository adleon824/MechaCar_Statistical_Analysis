# MechaCar_Statistical_Analysis


Linear Regression to Predict MPG

The vehicle length had a p-value of 2.60e-12 and is the strongest contributor of non-random variance is the ground clearance with a p-value of 5.21e-8.  The slope coefficients contain significant non-zero values and the p-values are less than the significance level of p=0.05. Our r^2 value is 0.7149, which means the model does have good predictive power for the mpg. 


Summary Statistics on Suspension Coils

The variance of all three lots in tandem falls under the maximum vvariance of 100 PSI with a variance of 62 PSI. The major contributor to the variance is lot 3 with a variance of 170 PSI  with the other two having variances below 8 PSI.  Lot 3 does not meet the maximum requirment with a variance of 170 PSI.  Other than that, the manufacturing data meets the maxmimum variance in PSI requirement.


T-Tests on Suspension Coils

The sample mean from the first t-test was not statistically different from the population mean of 1500 PSI with a p-value of 0.06.  However, when we perform t-tests on the individual lots, we can see that although lots 1 and 2 are not statistically different from the population mean with p-values of 1 and 0.06 respectively, lot 3 does have a mean which is statistically different from the population mean with a p-value of 0.04.


Study Design

We need to address a few variables that may benefit our customers when comparing the performance of the MechaCar against the competition.  Cost, city, highway fuel efficiency, horsepower, safety rating, and carbon waste output.  We will test to see if the MechaCar has statistically significant differences in these metrics compared to other competing models.  The null hypothesis is that these variables do not vary significantly from the competition, and the alternative hypothesis is that the MechaCar does vary significantly in these metrics compared to its competitors.  We will perform one-tailed t-tests in order to determine if the MechaCar has higherr or lower observed vallues in these variables than the competition, according to which direction the customer prefers.  The customer wants a lower cost, the city and highway fuel effficiency to be higher, higher horsepower, higher safety rating, and a lower carbon waste output.  We would need the cost, fuel efficiency, horsepower, safety rating, and carbon waste output data from the MechaCar and its competitors in order to run these statistical tests.
