## Intro to business problem 
Home Credit is a financial services provider specializing in lending to individuals with little or no credit history, empowering them with easy and safe access to financing. It is crucial for Home Credit to accurately assess a customer’s ability to repay in order to identify reliable target customers. By effectively predicting repayment capability, Home Credit can responsibly extend credit to a larger customer base while minimizing financial risk to the company and its investors.

## Key insights from Analysis 
Key insights identified through my analysis is that external credit scores are the most powerful predictors for loan default risk.  The higher the score, the lower the probability of loan default.  Age and employment duration have smaller but meaningful contributions.  My analysis suggests that older, more experienced customers are slightly less likely to default on the loan. Individual characteristics like gender and income when analyzed in isolation have unreliable predictive power, no better than a 50/50 coin flip.  

The log model with more variables showed decent performance for predictive accuracy.  The weighted tree performed slightly below the log model1, but did provide valuable insights in terms of class recognition.  

I will continue with other models to see if predictive power can be increased. Looking into models such as random forest or gradient boosted trees to combine interpretability and predictive power. I hope to be able to develop a model that Home Credit can better target high-risk customers while improving overall approval efficiency.  

