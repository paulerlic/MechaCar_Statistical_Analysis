# MechaCar_Statistical_Analysis

## Linear Regression Analysis
![Regression](https://user-images.githubusercontent.com/86337035/159983681-47c3a3dc-3ea0-4b1d-86f5-30c9c8a84102.png)

Variables : Vehicle length, vehicle weight, and ground clearance. 
All of these variables had p-values below the .05 alpha level of significance. 
AWD and spoiler angle returned p-values of 0.307 and 0.185 these variables provide no signifcant amount of non-random variance to mpg values. 


## Technical Analysis
![Tech](https://user-images.githubusercontent.com/86337035/159984094-537c9b4f-1fb2-492c-9fd8-42929e077f30.png)

This is a summary of the dataset showing the following:  
    - Average PSI of 1498.78  
    - Median PSI of 1500 
    - Variance of 62.29 
    - Standard deviation is 7.89

![Tech 2](https://user-images.githubusercontent.com/86337035/159984245-f9d50b4a-3cb4-497f-9979-a7e185278d18.png)

    - Lot 1 : Mean and median PSI of 1500, variance of 0.98, and a standard deviation of 0.99.
    - Lot 2 : Mean PSI of 1500.2, median of 1500, variance of 7.47, and a standard deviation of 2.73.
    - Lot 3 : Mean PSI of 1496.14, median of 1498.5, variance of 170.29, and a standard deviation of 13.05.


## T-Test on Suspension Coils
![Ttest](https://user-images.githubusercontent.com/86337035/159984339-a1ea7fc4-2a4c-46d9-814f-5c346c4e2419.png)

Our T-Test returned came back with a p-value of 0.06028. We failed to reject the null hypothesis and can confirm there is no evidence that average PSI across manufacturing lots differs from the population mean of 1500 PSI.

![Ttest 2](https://user-images.githubusercontent.com/86337035/159984453-4b7915c2-0a17-422c-8272-21a28d23ff3f.png)
With a p-value of 1, we fail to reject the null hypothesis and conclude that Manufacturing Lot 1 does not have a significantly different mean PSI from the population mean of 1500 PSI.

![Ttest 3](https://user-images.githubusercontent.com/86337035/159984570-d3fc4964-e364-44de-b9d4-b8ef0c0cc412.png)
With a p-value of 0.6072 and an alpha significance level of 0.05, we fail to reject the null hypothesis and conclude that there is not enough evidence to confirm that Manufacturing Lot 2 has a different average PSI from the population mean of 1500 PSI.

![Ttest 4](https://user-images.githubusercontent.com/86337035/159984646-bfc12a2e-cabf-4b75-8d2b-b47933704a78.png)
However this time, with a p-value of 0.04168, and an alpha significance level of 0.05, we reject the null hypothesis and can show there is sufficient evidence to conclude that Manufacturing Lot 3 has a significantly different average PSI from the population mean of 1500 PSI.


## Study Design: MechaCar vs Competition

    ### Description: We are trying to see how MechaCar stacks up against the competitions cars, we could look at MPG, consumer ratings, costs, etc. These variables are pretty good to look at but from a macro perspective most modern day cars are relativley similar in terms of performance, partly due to stiff competition in the automotive market and partly due to enviromental regulations. Instead we are going to look at vehicle accessory options, and how MechaCar stacks up against the competition. Specifically I want to take a look at the number of cup holders in a car, it sounds very strange but the number of cup holders in a car has been proven to have an effect on a consumers purchasing decsion. 
    
    ### Data Need: We will collect data on the number of cup holders for each make and model that MechaCar offers and we will collect the same data from other auto manufacturers whose vehicles are in the same class as MechaCars (ie price, size, MPG, and other standard info). We also need to gather the sales results of all the cars invloved, this will serve as the marker telling us if auto sales are impacted by the number of cupholders in a car.  It is important that we compare only the vehicles from the competition that are similar to MechaCars vehicles, this helps us reduce any bias in our analysis.    

    - Null Hypothesis: The number of cupholders in a car has no impact on sales levels compared to other similar cars in the automotive industry. 
    - Alternative Hypothesis: The number of cupholders in a car has a significantly impact on sales levels compared to other similar cars in the automotive industry.

    ### Method:  We will conduct a one-sample t-test of the count of cup holders in MechaCar models compared to the count of cup holders from other manufacturers and the models of cars that they offer that are similar to MechaCars to see if there is a signifcant difference. Next, we will conduct one-sample t-tests to assess whether MechaCar has a significantly different sales numbers compared to each individual manufacturer.



