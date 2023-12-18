# Prediction of Credit Card Payment Default
### ABSTRACT

In today’s world, online and card-based payment systems, the market for digital payments is exploding and with such a shift comes the growing issue credit card default. As increasingly more purchasers depend upon the credit card to pay their ordinary purchases in online and bodily retail store, the quantity of issued credit cards and the overpowering quantity of credit card debt via way of means of the cardholders have swiftly increased. Therefore, maximum economic establishments need to address the troubles of credit card default further to the credit card fraud. According to the Federal Reserve financial statistics, the default charge on credit card loans throughout all industrial banks is at an all-time high.

The primary objective of this project is to identify patterns of the customers that uses credit card classify them if they will default on a payment or not. We intend to achieve this by using various
Machine learning techniques and selecting the best classification algorithms that successfully classify if a person will default on a payment or not. This is done by initially performing Exploratory Data Analysis (EDA) with the features of the dataset. The relationships of various features with each other are studied followed by feature engineering and feature selection.
By adopting Supervised Machine Learning models, the basic factors which affect the probability of a credit card default can be highlighted. In particular, we have used classification models like Logistic Regression, Support Vector Machines (SVM), Gaussian Naïve Bayes, Neural Networks.

### DATA DESCRIPTION
This research employed a binary variable, default payment (Yes = 1, No = 0), as the response
variable. This study reviewed the literature and used the following 23 variables as explanatory
variables:

X1: Amount of the given credit (USD): it includes both the individual consumer credit and his/her family (supplementary) credit.

X2: Gender (1 = male; 2 = female).

X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).

X4: Marital status (1 = married; 2 = single; 3 = divorced).

X5: Age (year).

X6 - X11: History of past payment. The past monthly payment records (from April to
September, 2005) as follows:
X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;
X11 = the repayment status in April, 2005.
The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one
month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 =
payment delay for nine months and above.

X12-X17: Amount of bill statement (USD).
X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August,
2005; . . .; X17 = amount of bill statement in April, 2005.

X18-X23: Amount of previous payment (USD).
X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .; X23 = amount
paid in April, 2005.
