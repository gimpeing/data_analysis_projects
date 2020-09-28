# Project 3: A/B Test

In this project, I worked on the test results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product.   
My goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Contents:
### Part 1 : Probability
Calculate the observed statistics, that is the propability of conversion from the control and experimental group. Control group is given the old page, and experimental group is given the new page.

### Part 2 : A/B Test
Define the hypothesis: 
$$H_0: p_{new} - p_{old} \leq 0 $$
$$H_1: p_{new} - p_{old} > 0 $$

Simulate the sampling distribution for difference in **converted** between the two pages under the null. Compute the p-value to determine the statistical significance of the observed difference statistics. 

### Part 3 : Logistic Regression
Using the **statsmodels** to fit the logistic model to see if there is a significant difference in conversion based on the landing page a user receives, user's country of origin and the interaction term among the two.

## Conclusion:
The **A/B test** is carried out at Type I error rate (or alpha risk) of 5%.
The results of the p-value is 0.91, that is > 0.05, which we fail to reject the null-hypothesis as the statistic is likely from the null. This suggests that the converted rate with the new page is truely less than or equal to the converted rate with the old page, within the experiment duration of 21 days. 

**Logistic regression** is carried out to consider the independent variables that influence whether or not an individual converts. Results found out that the landing page, and country of user and the interaction term among the two are not signifianct in helping to predict if a user is converted or not. The high p-value suggests that we fail to reject the null hypothesis.

As summary, data from the 21 days of experiment, roughly equal number of users from control (old page) and experiment (new page) groups shows conclude that insufficient evidence of the new treatment page leads to more conversions.


```python

```
