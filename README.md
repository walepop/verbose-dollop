# verbose-dollop
# Problem
Machine Learning beginning for churn in the Telecommunication Industry. Churn has long been a major problem in the telecommunication industry as users can easily swap to a different service provider. This prompts service providers to identify patterns that make a user churn. The information helps the service provider know the certain conditions that users are more likely to churn. The service providers can suggest products or services that will navigate such conditions to facilitate customer churn. The customer dataset is gotten from Kaggle.

# Data Prepocessing 
● Data transformation: The datasets variables were converted to factors.
● Data Cleaning: The columns 10:15 contained values that were not consistent. Values such as "No internet Service" and "No phone service" were converted to "No". Values in the column Senior citizen were changed from 0 and 1 to No and Yes
● Data Selection: The column containing customer_Id was removed as it was not going to be used for analysis.

# Exploring Data Analysis
● Correlation was conducted for columns Monthly Charges and Total Charges. It was discovered that the two columns were correlated so one of the values was removed.
● Bar charts were made to identify the distribution of the remaining variables. It was ascertained that the distribution so there was no need for under sampling the datasets

# Data Analysis
Classification algorithms were used to identify if a customer will churn or not. 70% of the dataset was partitioned for training and the rest for test_data.
● I used logistic regression algorithm on the dataset. The accuracy was 80% and the most important variables from the algorithm that determined churn were tenure, contract and paperless billing method.
● Decision tree was also used for building the model, the algorithm indicated that Contract is the most important feature to churn or not to churn. Users on a year or two contract are less likely to churn whether they are on paper billing or not. Users with less than tenure of 2 months are the most likely to churn. The accuracy of the model was 76%.
● Random forest was also used. It delivered an accuracy of 79%. The most important features according to RM are Tenure, Contract and Monthly Charges.


# Conclusion.
From the analysis, I can deduce that the most important features for determining customer churn is Tenure and Contract. The other important features are Paperless billing, Monthly charges, Internet Service. Consumers that are on monthly contract with less than 2 month tenure are the most likely to churn. For the company to retain these customers, we need to find the characteristics that makes a customer want to retain the company subscriptions for more than 2 months. Then we can devise the products that encourage these customers to remain with the company.

I would suggest that the service providers continue to offer long-term contracts. The service provider equally need to provide incentivised packages that will encourage a new user to use their service  for longer than 2 months. It is also possible that the company offers new users benefits upon their initial signing and when these benefits expire, they stop using the product. More research will be needed to establish this assumption. If that is the case, better packages need to be offered and a different beneficial package that ensures a long-term usage need to be offered to the consumers. Example instead of free minutes and internet upon new signing, a bonus package could be offered periodically and randomly at 2 months tenure.


