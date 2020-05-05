
# Modeling
Our team has decided to build linear regression model bacause of its great interpretability.
## Feature Engineering

Our team has divided the whole time period into several period based on the change of social distancing status (when this status changes, we see it as a new time period). And we choose rate as dependent variable instead of case number because rate is more comparable between different states since the total confirmed and death cases may vary a lot from state to state.
Then, we have standardized the data before modeling for better model-performance.

## Modeling process
We have built two linear regression models to predict infection rate and death rate separately using the independent variables regarding education, medical resource, public transportation, social distancing, aging and population density.

### Modeling results
Here's all the correlations among each features:
![Model Features Coefficients and P-value](https://github.com/Mandy-Gu/COVID-19-Analysis/blob/master/Modeling/feathre_correlation.png?raw=true)

Here's all the coefficients and p-value for both models:

![Model Features Coefficients and P-value](https://github.com/Mandy-Gu/COVID-19-Analysis/blob/master/Modeling/all_model_coefficients.png?raw=true)


As we can see here, for most indices about social distancing, they have a negative impact on the infection and death rates. And among all of the indices, social gathering ban has the greatest impact.


