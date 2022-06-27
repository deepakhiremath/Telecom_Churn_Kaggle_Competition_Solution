# Telecom_Churn_Kaggle_Competition_Solution


# Kaggle competition:
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

# Objective:
The main goal of the case study is to build ML models to predict churn. The predictive model that you’re going to build will the following purposes:

1. It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.

2. It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.

3. Even though overall accuracy will be your primary evaluation metric, you should also mention other metrics like precision, recall, etc. for the different models that can be used for evaluation purposes based on different business objectives. For example, in this problem statement, one business goal can be to build an ML model that identifies customers who'll definitely churn with more accuracy as compared to the ones who'll not churn. Make sure you mention which metric can be used in such scenarios.

 4. Recommend strategies to manage customer churn based on your observations.

# Conclusion:
While applying PCA on Logistic Regression, Sensitivity has dropped by 3% when we tried with LR-PCA, so we are using the LR-RFE method to generate data it gave us better accuracy and Sensitivity(Accuracy:- 0.815460883857798, Sensitivity:- 0.9111229377328366)
After all the model building and several submissions made in kaggle we have concluded that Random Forest classifier has given best results (Accuracy:- 0.9335383473396781, Sensitivity:- 0.9269824374667376, Specificity:- 0.9400454281337489) on test data. On unknown data , it has given 94% in kaggle.
We are considering that these features are of high importance for telecom company to consider inorder to decrease the churn of customers:

roam_ic_mou
roam_og_mou
loc_og_mou
total_og_mou
loc_ic_t2t_mou
loc_ic_t2m_mou
loc_ic_mou
total_ic_mou
total_rech_amt
max_rech_amt
