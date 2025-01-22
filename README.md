# Comparing-Classifiers

## Practical Application III: Comparing Classifiers

### Findings

#### Business Understanding
The goal is to predict whether a customer will subscribe to a term deposit based on various features.

#### Data Cleaning
The notebook includes steps for:
- Handling missing values
- Encoding categorical variables
- Balancing classes using SMOTE

#### Descriptive and Inferential Statistics
The notebook provides a correct and concise interpretation of the data, including summary statistics and visualizations.

### Key Insights

#### Feature Importance
- **Duration**: The length of the last contact with the customer is the most significant factor. Longer calls are strongly associated with a higher likelihood of subscription.
- **Euribor3m**: The 3-month Euribor rate is also important, indicating that economic conditions play a role in the decision.
- **Age**: The age of the customer is another significant factor, suggesting that different age groups have varying propensities to subscribe.
- **Employment-related features**: Features like the number of employees and employment variation rate also influence the likelihood, reflecting the customer's employment status and economic environment.

#### Model Performance
- The model has a high overall accuracy (91%), meaning it is generally good at predicting whether a customer will subscribe.
- However, the model performs better at predicting customers who do not subscribe (class 0) compared to those who do (class 1). This is evident from the higher precision, recall, and F1-score for class 0.

### Practical Implications
- **Targeted Marketing**: The bank can focus on customers who have longer call durations, are within certain age groups, and are influenced by economic conditions.
- **Improving Recall for Class 1**: Since the recall for class 1 (subscribers) is lower, the bank might consider additional features or different models to better identify potential subscribers.

### Next Steps and Recommendations
- **Feature Engineering**: Explore additional features that might improve the model's performance, especially for class 1.
- **Model Tuning**: Experiment with hyperparameter tuning and different algorithms to enhance recall for subscribers.
- **Business Strategy**: Implement targeted marketing strategies based on the identified key features to improve subscription rates.
