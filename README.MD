

## **Project Overview**

SyriaTel, telecommunications company, is facing a significant challenge linked to customer churn. Churn is when customers decide to terminate their subscriptions with companies by terminating using their services. SyriaTel is experiencing churn with customer resulting in revenue loss. To address this issue, SyriaTel aims to build a predictive model to identify customers who are likely to churn. By proactively targeting these at-risk customers with retention strategies, SyriaTel hopes to reduce churn rates and retain valuable customers.

### **INTRODUCTION**
Imagine having the power to predict the future — not in a mystical sense, but when it comes to our customers. Churn prediction is like having a crystal ball for customer behavior in the world of telecommunications. It allows us to see storms before they hit, giving us invaluable time to prepare and, more importantly, to act.
In this project I’ll dive into predictive analysis to explore how churn prediction can be a game changer for Syria Tel a telecommunications company and using the insights to make informed decisions and put in place strategies to mitigate churn rate for clients highly likely to churn from Syria Tel.


### **Challenges**
Managing and analyzing diverse data types and large volumes can be challenging.
Inaccurate or incomplete data can lead to biased analysis and predictions.
Churn events are often rare compared to non-churn events, leading to imbalanced datasets
The competitive landscape in the telecommunications industry can change rapidly.



### **Proposed Solution**
Based on our findings, we recommend the following:
Review International Plan: Given its importance in predicting churn, it would be beneficial to review the structure and pricing of the international plan to ensure it meets customer needs.
Improve Customer Service: The number of customer service calls is a strong predictor of churn. Efforts should be made to improve the customer service experience to reduce the likelihood of churn.
Analyze Pricing Structure: Customers with a higher total charge are more likely to churn. A review of pricing strategies and structures could help to ensure they are competitive and provide value to customers.
Address the issue of network coverage for some states.

Data Science Process Used:
The Data Science Process that is adhered to in this analysis is the CRISP-DM Process.

**1. Business Understanding**
Telecoms prioritize acquiring and retaining subscribers. Customer attrition is a major concern in the competitive telecom sector, impacting companies like Syriatel. To address churn effectively, telecom businesses must recognize its underlying factors and predict them accurately. Businesses can proactively identify customers at risk of leaving and devise personalized retention strategies. Proactive churn management reduces revenue losses and improves customer satisfaction.

**2. Data Understanding**
What Data Did We Use?
The SyriaTel Dataset was retrieved from Kaggle. It contains information on customers. The data includes various details like the state the customer is from, how long they've been a customer, whether they have an international plan or voice mail plan, how many customer service calls they've made, and many more.
3. Data Preparation:
In this stage, data is transformed, cleaned, and preprocessed to make it suitable for analysis. This included;
Data Type conversion, dealing with multicollinearity, and splitting the data.
4. Modeling
We tested our model to see how well it could predict customer churn. We fitted four models, Decision trees, Random forests, Logistic regression, and Gradient boost model. Our best model was the Gradient Boost Classifier, which had a recall score of about 81.2%.
Model Evaluation:
A combination of metrics such as accuracy, precision, recall, F1-score, and ROC- AUC can be used to evaluate the performance of the model and ensure that it meets the business requirements and goals of the telecom company.
The churn prediction models seem to have reasonably good performance based on the metrics used (accuracy, precision, recall, and F1-score), with Gradient Boosting performing the best with an Accuracy of 94.26% and Recall of 72% after tuning.
.
Additionally, the key features that were shown to influence whether a customer would churn or not can be seen in the bar plot displayed below. We can note that the total expenditure is a key predicting variable.

**Conclusions**
Factors such as the number of customer service calls, whether the customer has an international plan, and the total day's minutes and charges were significant predictors of customer churn. Interestingly, we found that customers with an international plan are more likely to churn.

**What's Next?**
Based on our findings, we recommend SyriaTel to:
Review International Plan: Review the structure and pricing of the international plan to ensure it meets customer needs.
Improve Customer Service: Improve the customer service experience to reduce the likelihood of churn.
Analyze Pricing Structure: A review of pricing strategies and structures could help to ensure they are competitive and provide value to customers.

# Customer-Churn-Prediction
