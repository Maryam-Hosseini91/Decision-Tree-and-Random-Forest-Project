# Decision-Tree-and-Random-Forest-Project
Decision Tree and Random Forest are popular machine learning algorithms used for both classification and regression tasks. Let's discuss each algorithm in more detail:

1. Decision Tree:
   - A decision tree is a flowchart-like structure where each internal node represents a feature, each branch represents a decision rule, and each leaf node represents the outcome.
   - The tree is built by recursively partitioning the data based on the values of the features, aiming to create homogeneous subsets with respect to the target variable.
   - At each internal node, the decision tree algorithm selects the best feature to split the data based on certain criteria such as Gini impurity or information gain.
   - Decision trees are easy to understand and interpret, and they can handle both categorical and numerical features.
   - However, decision trees tend to overfit the training data, meaning they may have poor generalization performance on unseen data. This is where Random Forest comes into play.

2. Random Forest:
   - Random Forest is an ensemble learning method that combines multiple decision trees to make predictions. It is based on the concept of bagging (bootstrap aggregating).
   - The random forest algorithm creates an ensemble of decision trees, where each tree is trained on a random subset of the training data (sampling with replacement) and a random subset of the features.
   - During the prediction phase, each tree in the forest independently predicts the outcome, and the final prediction is determined by majority voting (classification) or averaging (regression) the individual tree predictions.
   - Random Forest improves upon the weaknesses of decision trees by reducing overfitting and increasing the model's generalization performance.
   - It can handle a large number of features and provides estimates of feature importance, allowing for feature selection.
   - Random Forest is also robust to noisy data and outliers.
   - However, compared to a single decision tree, random forests can be computationally more expensive and harder to interpret.

Both Decision Tree and Random Forest have their advantages and disadvantages. Decision trees are simple and interpretable but prone to overfitting, while Random Forest provides better generalization but is more complex and less interpretable. The choice between the two depends on the specific problem, the available data, and the trade-offs between interpretability and performance.

## Project:
For this project we will be exploring publicly available data from LendingClub.com. Lending Club connects people who need money (borrowers) with people who have money (investors). Hopefully, as an investor you would want to invest in people who showed a profile of having a high probability of paying you back. We will try to create a model that will help predict this.

Lending club had a very interesting year in 2016, so let's check out some of their data and keep the context in mind. This data is from before they even went public.

We will use lending data from 2007-2010 and be trying to classify and predict whether or not the borrower paid back their loan in full.
##### The Algoriths used for this project are:  Decision Tree and Random Forest

#### Here are what the columns represent:

* credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
* purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
* int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
* installment: The monthly installments owed by the borrower if the loan is funded.
* log.annual.inc: The natural log of the self-reported annual income of the borrower.
* dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
* fico: The FICO credit score of the borrower.
* days.with.cr.line: The number of days the borrower has had a credit line.
* revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
* revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
* inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
* delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
* pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).




