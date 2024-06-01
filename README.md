# <div align="center">Demo Data for Internet Customer Churn Prediction</div>

The Foghlaim Meaisin Software recently launched the Foghlaim Meaisin Internet Customer Churn Prediction software

Our homepage is here

https://foghlaimmeaisin.com/

You can try our demo data onto the Internet Customer Churn Prediction System here

https://github.com/mekongsoft/custchurn-demo

We have created 12 models to compare their performances on Internet Customer Churn Prediction

* Adaboost
* CatBoost
* Decision Tree Classifier
* Gaussian NB
* Gradient boost classifier
* Kernel SVM
* KNN
* Logistic Regression
* Random Forest
* SVC
* Voting Classifier
* XGBoost

in which the performance of Adaboost has been the best model to predict Internet Customer Churn,
This is our accuracy evaluation

                   Model  Accuracy  Precision    Recall  F1 SCore  F2 Score

0               Adaboost  0.812322   0.687927  0.538324  0.604000  0.562803

1               CatBoost  0.776303   0.680162  0.299465  0.415842  0.337214

2      Voting Classifier  0.808531   0.675615  0.538324  0.599206  0.561130

3         Gradient Boost  0.804265   0.669725  0.520499  0.585757  0.544776

4             Kernel SVM  0.793839   0.659898  0.463458  0.544503  0.492798

5    Logistic Regression  0.805687   0.658281  0.559715  0.605010  0.576994

6          Random Forest  0.796682   0.650685  0.508021  0.570571  0.531320

7   K-Nearest Neighbours  0.789100   0.628889  0.504456  0.559842  0.525241

8           SVM (Linear)  0.788626   0.628635  0.500891  0.557540  0.522111

9                XGBoost  0.772986   0.581349  0.522282  0.550235  0.533115

10           Naive Bayes  0.756872   0.531088  0.730838  0.615154  0.679708

11         Decision Tree  0.732701   0.497364  0.504456  0.500885  0.503022

So the best is Adaboost (81.23%), the second is Voting Classifier (80.85%), the third is Logistic Regression (80.57%) and the fourth is Gradient Boost (80.42%), then the rest are below 80%.

This is how we work:

On our web form, enter the parameter for an Internet Customer, then select one of the 12 models as below
![Marketing](./marketing/BackendAPI_Form.png)

Then click Submit to know the possibility if this Customer can churn or not

![Marketing](./marketing/BackendAPI_Predict.png)

These below are the True Positive rate for Adaboost, CatBoost and XGBoost

![Marketing](./marketing/AdaboostTruePositive.png)

![Marketing](./marketing/CatBoostTruePositive.png)

![Marketing](./marketing/XGBoostTruePositive.png)

We have also reached the similar conclusions to Internet Customer Churn Prediction:

a) Internet customers with Month-to-Month Contract opted to move out than One-Year Contracted or Two-Year Contracted customers

b) Internet customers who pay by Credit-Card Automatic Transfer, Bank Automatic Transfer or Mailed Check are less likely to churn

c) Internet customers having DSL service are less likely to churn than Fibre optic service

d) Internet customers without dependents are more likely to churn

e) Internet customers churn due to lack of online security

f) Most of the senior (elder) Internet customers churn

g) Internet customers with Paperless Billing are more likely to churn

h) Internet customers with no TechSupport are more likely to churn

i) Internet customers with higher Monthly Charges are also more likely to churn

j) Newer Internet customers are more likely to churn

This Repo is for Markerting Demo tasks.

https://github.com/mekongsoft/custchurn-demo

COPYRIGHT@2023 OF FOGHLAIM MEAISIN SOFTWARE, CALGARY, ALBERTA, CANADA.