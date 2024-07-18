# Long-rains-effect-on-Bean-Leaves
Summarizes disease severity and incidence on bean leaves across five counties in western region by combining tests for significant differences between disease severity and incidences in the counties and sub counties studied. Regression analysis was also performed to establish the relationship between disease incidence and severity and by what extend. Find the publication here https://docs.google.com/document/d/12FYNgXLz0Ek89fBqbaYe-iquax2TMVte/edit?usp=sharing&ouid=113647396333517765932&rtpof=true&sd=true
## Test for significance differences in disease incidence in counties
H0: μ1. = μ2. =⋯= μr
![Screenshot 2024-07-18 035848](https://github.com/user-attachments/assets/ca3a6dd4-99d1-48be-a3fc-c841b12d10ad)
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
![Screenshot 2024-07-18 035926](https://github.com/user-attachments/assets/88453b44-e8a6-4a8d-b131-c77cceb91247)

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
![Screenshot 2024-07-18 040025](https://github.com/user-attachments/assets/d341321e-969e-4273-8e9d-ccfbf72dce95)

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
![Screenshot 2024-07-18 040124](https://github.com/user-attachments/assets/f45053e1-ceb5-4e1a-b5eb-294302729a3f)
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




