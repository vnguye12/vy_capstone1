# vy_capstone1 LOAN ANALYSIS
Small and medium enterprises (SMEs) are businesses that have revenues, assets and a number of employees below a certain threshold. Although the definition of SMEs is different from country to country, their important role in the economy is undeniable. They are one of the strongest drivers of economic development, innovation and employment. The access to finance is recognized as the greatest obstacle to the growth of SMEs. The financing gap for SMEs is huge. Millions of SMEs have unmet financing needs all over the world. Lenders who can address this matter have great growing potential. The challenge for these lenders is how to manage loan risk efficiently and make accurate decisions. There are two basic risks here: one is a business loss results from not lending the good candidates, and the other is the financial loss for lending the candidates at bad risk. Therefore, the ability to recognize good candidates who are able to make payments is crucial.

This project focuses on using classification models in supervised machine learining (Logistic Regression, SVM, kNN, Random Forest, Decision Tree, Naive Bayes, Stochastic Gradient Descent) to predict whether a company is going to miss payments if money is lent. The dataset is taken from a South African digital lender. The join data set consists of 1346 rows, representing 1346 companies who are already their customers, and 49 columns, representing the features. This dataset has continuous and categorical data along with missing values. The variable of interest is “bad” containing the payment history of these companies, either 1 meaning company missed payments or 0 meaning company did not miss payments.

The lender can use the best model to estimate the probability of missing payment of an applicant and make decision based on these infomation. They can also compute the best cut off ( A companies will be lent if its probability of missing payments is less than or equal to the cut off) using the interest rate, requested disbursememt amounts and probability of missing payments.

The outline of this project is:
* Proposal
* Data Wrangling
* Analyze by describing data
* Variables Selection
* Dimensionality Reduction PCA
* Analyze by pivoting features
* Variables Distribution_Visualization
* Machine Learning Algorithms
* Disbursements and Threshold
