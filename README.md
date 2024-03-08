
![image](https://github.com/Noahkandie/Data-driven-marketing/assets/83200580/431b37c3-e091-483f-8ba1-8f6781b53b09)


## Business Understanding:
The goal of this project is to leverage customer data from a bank to improve marketing effectiveness and customer engagement. This involves understanding customer demographics, predicting customer response to marketing campaigns, identifying effective marketing channels, and improving customer retention strategies.

The bank aims to achieve the following objectives:

1. Understanding Customer Demographics: Analyze demographic characteristics such as age, education, and marital status to identify key customer segments and their preferences.

2. Predicting Customer Response: Develop predictive models to forecast whether a customer is likely to respond positively to marketing campaigns based on past interactions and other relevant factors.

3. Identifying Effective Marketing Channels: Evaluate the performance of different communication channels and campaign strategies to determine the most effective in engaging customers and driving conversions.

4. Improving Customer Retention: Identify factors influencing customer churn and develop strategies to retain existing customers through personalized incentives or improved services.

## Data 
The dataset contains information about bank customers, including demographic details, account balances, contact information, and previous campaign outcomes. It consists of 45,211 entries with 17 columns, including both numerical and categorical features.

## Exploratory Data Analysis 
*Target Variable*: The target variable 'y' indicates whether a customer subscribed to a term deposit, with a significant class imbalance observed.
*Age Analysis*: Most customers fall within the age range of 33 to 48 years, with older customers having higher account balances.
*Job and Education*: Certain job types (e.g., management, retired) and education levels (e.g., tertiary) appear to be associated with higher subscription rates.
Marital Status and Loan: Married customers and those without loans tend to have higher subscription rates.


## Modeling:
Various classification models including Logistic Regression, K-Nearest Neighbors, Naive Bayes, Decision Tree, and Random Forest were trained and evaluated on the dataset. Random Forest exhibited the highest accuracy and F1 score among the models, indicating its effectiveness in predicting customer subscriptions.

### Undersampling:
To address class imbalance, undersampling was performed, resulting in a balanced dataset with equal instances of both classes. Models trained on this balanced dataset showed improved performance, particularly in precision, recall, and F1 score for the minority class.

### Recommender System:
A simple recommender system was implemented based on cosine similarity to recommend items similar to a target class value.

## Conclusions:
- The original dataset's class imbalance negatively affected model performance.
- Undersampling significantly improved model performance, especially for the minority class.
- Certain demographic and behavioral features were found to be correlated with subscription likelihood.
