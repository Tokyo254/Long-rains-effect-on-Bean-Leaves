# Long-rains-effect-on-Bean-Leaves
Summarizes disease severity and incidence on bean leaves across five counties in western region by combining several statistical procedures in R.
## average disease incidence and viral disease severity per county and subcounty N/B Incidence is (%) and severity is scale (1-3)
County	Sub-County	Incidence (%)	Severity (1-3)
Bungoma	Bungoma	9.30	1.05
Bungoma	Bungoma Central	18.00	1.50
Bungoma	Bungoma N/S	10.00	1.00
Bungoma	Bungoma West	14.60	1.10
Bungoma	Mayanja -kibuke	16.80	1.50
Busia	Butula	18.00	1.40
Busia	Matayos	14.50	1.80
Kakamega	Kakamega East	17.48	1.48
Kakamega	Kakamega South	18.67	1.67
Kakamega	Kakamega West	22.80	1.67
Kakamega	Lugari	14.47	1.47
Nandi	Nandi South	7.00	1.30
Vihiga	Hamisi	23.70	1.85
Vihiga	Sabatia	10.00	1.00
## Test for significance differences in disease incidence in counties
H0: μ1. = μ2. =⋯= μr
County	Incidence1/50	Incidence 2/50	Incidence 3/50	Incidence 4/50	Incidence 5/50
Bungoma	15.47	16.40	16.13	16.67	17.13
Busia	17.33	17.00	18.33	19.00	18.00
Kakamega	14.82	19.76	18.12	18.88	18.88
Nandi	15	15	11	14	17.5
Vihiga	10.6	14	11.6	9.4	12
![Screenshot 2024-07-18 034357](https://github.com/user-attachments/assets/94b5d492-8c19-43fd-8180-53de11b58cf5)
H0: there is no significant difference in counties incidence rates.
Since the p-value for the counties = 1.72E-05< .05 = α we reject the null hypothesis, and so at the 95% level of confidence we conclude there is significant difference in the counties incident rates.
H0: there is no significant difference in incidence rates (population) means for the crop types
Since the p-value for the incidence rates = .1446 > .05 = α ,we can’t reject the null hypothesis, and so at 95% level of confidence we conclude there is no significant difference in the incidence rates for the four counties studied.

Tukey multiple pairwise-comparisons

It can be seen from the output the counties 
Busia-Bungoma     
Kakamega-Bungoma  
Nandi-Bungoma   
Kakamega-Busia
Nandi-Busia
Nandi-Kakamega
Vihiga-Nandi
all pairwise comparisons are not significant with an adjusted p-value > 0.05. This indicates significant differences in incidence rates for the interaction between the following counties mentioned above. 

## Test for significance differences in disease severity in counties
County	Severity 1	Severity 2	Severity 3	Severity 4	Severity 5
Bungoma	1.33	1.20	1.27	1.47	1.40
Busia	1.67	1.67	1.67	1.67	1.33
Kakamega	1.47	1.59	1.53	1.59	1.53
Nandi	2	2	1.5	1.5	2
Vihiga	1.4	1.4	1.2	1.2	1.4

H0: μ1. = μ2. =⋯= μr
![Screenshot 2024-07-18 034609](https://github.com/user-attachments/assets/2f4266e3-6e03-44a8-baf0-ee9ac27c14c9)
H0: there is no significant difference in counties.
Since the p-value for the counties = 0.0012< .05 = α we reject the null hypothesis, and so at the 95% level of confidence we conclude the difference in counties is significant.
H0: there is no significant difference in severity rates.
Since the p-value for the incidence rates = .6985 > .05 = α , we can’t reject the null hypothesis, and so at 95% level of confidence we conclude there is no significant difference in the severity rates counties studied.
Tukey multiple pairwise-comparisons

It can be seen from the output that the interaction between the following counties 
Busia-Bungoma     
Kakamega-Bungoma  
Nandi-Bungoma   
Vihiga-Bungoma
Kakamega-Busia
Nandi-Busia
Nandi-Kakamega
Vihiga-Kakamega
all pairwise comparisons are not significant with an adjusted p-value > 0.05. This indicates significant differences in severity rates for the interaction between the following counties mentioned above. 

## Test for significance differences in disease incidence in sub-counties
H0: μ1. = μ2. =⋯= μr
Sub Counties	Incidence1/50	Incidence 2/50	Incidence 3/50	Incidence 4/50	Incidence 5/50
Bungoma	8	9.5	10.5	9.5	9
Bungoma Central	16.75	19.75	16.75	18.75	18
Bungoma West	12.5	18	15.5	12.5	14.5
Mayanja -kibuke	15	20	15.5	15.5	18
Butula	20	10	15	20	25
Matayos	15	15	11	14	17.5
Kakamega East	13.375	22.375	16.75	17.375	17.5
Kakamega South	20	15.66666667	20.33333333	20	17.33333333
Kakamega West	18.33333333	26	23.33333333	22.66666667	23.66666667
Lugari	10	10.66666667	14.33333333	18	19.33333333
Nandi South	6.5	7.5	8.5	5.5	7
Hamisi	23	22.75	22.5	24.25	26
Sabatia	10	15	10	5	10
![Screenshot 2024-07-13 105043](https://github.com/user-attachments/assets/577a8e14-acc4-442d-b925-03844625008a)
H0: there is no significant difference in sub-counties.
Since the p-value for the sub-counties = 4.61E-14< .05 = α we reject the null hypothesis, and so at the 95% level of confidence we conclude that the difference in sub-counties is significant.
H0: there is no significant difference in severity rates.
Since the p-value for the incidence rates = .6985 > .05 = α , we can’t reject the null hypothesis, and so at 95% level of confidence we conclude there is no significant difference in the incidence rates counties studied.
Tukey multiple pairwise-comparisons

It can be seen from the output that the interaction between the following counties 
Bungoma Central-Bungoma           
Hamisi-Bungoma                   
Kakamega East-Bungoma             
Kakamega South-Bungoma            
Kakamega West-Bungoma            
Nandi South-Bungoma Central     
Hamisi-Bungoma West               
Nandi South-Kakamega East       
Nandi South-Kakamega South      
Sabatia-Kakamega South           
Mayanja -kibuke-Kakamega West    
Nandi South-Kakamega West       
Sabatia-Kakamega West           
Nandi South-Lugari               
Nandi South-Matayos             
Nandi South-Mayanja -kibuke    
all pairwise comparisons are significant with an adjusted p-value < 0.05. This indicates no significant differences in incidence rates between the counties listed above.  
## Test for significance differences in disease severity in sub-counties
Sub Counties	Severity 1	Severity 2	Severity 3	Severity 4	Severity 5
Bungoma	1	1	1	1	1.25
Bungoma Central	1.75	1.25	1.25	1.75	1.5
Bungoma West	1	1	1	1.5	1
Mayanja -kibuke	1.5	2	1.5	1	1.5
Butula	1	1	2	1	2
Matayos	2	2	1.5	1.5	2
Kakamega East	1.375	1.625	1.5	1.5	1.375
Kakamega South	1.666666667	1.666666667	1.333333333	2	1.666666667
Kakamega West	1.666666667	1.666666667	1.666666667	1.666666667	1.666666667
Lugari	1.333333333	1.333333333	1.666666667	1.333333333	1.666666667
Nandi South	1.5	1	1	1.5	1.5
Hamisi	1.75	2	1.75	2	1.75
Sabatia	1	1	1	1	1
![Screenshot 2024-07-13 114142](https://github.com/user-attachments/assets/e8f3cfa5-b9d2-4b79-9a54-6253a4693586)

H0: there is no significant difference in sub-counties.
Since the p-value for the sub-counties =2.08E-07< .05 = α we reject the null hypothesis, and so at the 95% level of confidence we conclude that the difference in sub-counties is significant.
H0: there is no significant difference in severity rates.
Since the p-value for the incidence rates = .738 > .05 = α, we can’t reject the null hypothesis, and so at 95% level of confidence we conclude there is no significant difference in the severity rates in counties studied.
Tukey multiple pairwise-comparisons
It can be seen from the output that the interaction between the following counties 
Bungoma Central-Bungoma           
Butula-Bungoma    
Matayos-Bungoma 
Hamisi-Bungoma West
Sabatia-Hamisi
Sabatia-Kakamega South
Sabatia-Kakamega West
Sabatia-Matayos   
## Correlation
all pairwise comparisons are significant with an adjusted p-value < 0.05. This indicates no significant differences in incidence rates between the counties listed above.  
The p-value is 1.538e-12 < 0.05 so the null hypothesis is rejected therefore it is statistically reasonable to conclude that there is significant positive correlation between incidence and severity based on the sample at The Pearson coefficient of 0.85781.
![Screenshot 2024-07-18 035311](https://github.com/user-attachments/assets/c7a0184d-3382-45e7-a924-fd97e03aeec9)

## Regression Analysis 
![Screenshot 2024-07-18 035422](https://github.com/user-attachments/assets/a7603472-541b-469c-a0b6-a61bd2ac9c35)

Residuals
Residuals:
     Min       1Q   Median       3Q      Max 
-0.77517 -0.14188 -0.02754   0.14428   0.67653 
A good model typically has residuals centred around zero with no extreme outliers.
Coefficients
Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 0.797618   0.076779   10.39 1.17e-12 ***
incidence   0.040731   0.003959   10.29 1.54e-12 ***
Intercept (Estimate = 0.797618): This is the predicted value of Severity when incidence is zero.
•	Std. Error: 0.076779, the standard error of the intercept estimate.
•	t value: 10.39, which is the estimate divided by its standard error.
•	Pr(>|t|) = 1.17e-12*: The p-value for the intercept, indicating it is highly significant (p < 0.001).
incidence (Estimate = 0.040731): For each one-unit increase in incidence, Severity increases by approximately 0.040731.
•	Std. Error: 0.003959, the standard error of the incidence estimate.
•	t value: 10.29, indicating the strength of the evidence against the null hypothesis.
•	Pr(>|t|) = 1.54e-12*: The p-value for the incidence coefficient, indicating it is highly significant (p < 0.001).
R-squared
Multiple R-squared:  0.7359,	Adjusted R-squared:  0.7289 
•	Multiple R-squared (0.7359): About 73.59% of the variance in Severity is explained by incidence.
•	Adjusted R-squared (0.7289): Adjusted for the number of predictors in the model, and slightly lower than R-squared.
Summary
•	The model shows a significant positive relationship between incidence and Severity.
•	The model explains approximately 73.59% of the variability in Severity.
•	Both the intercept and the slope are highly significant.
•	The small residual standard error and high R-squared values indicate a good fit.
This output suggests that incidence is a strong predictor of Severity in the data.




