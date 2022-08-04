# Predicting_Credit_Risk

In this assignment, I will be building a machine learning model that attempts to predict whether a loan will be approved or not.

## Background

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. This data will be used to 

I will be using this data to create machine learning models to classify the risk level of given loans. After that, I will be comparing the Logistic Regression model and Random Forest Classifier.

## Consider the models

I created and compared two models on this data: a logistic regression, and a random forests classifier (scale and unscale). I assumed that random forest classifier would perform better than logistic regression model in ML

## Conclusion and Results

### Results

LogisticRegressin unscaled score: 0.9918489475856377

LogisticRegressin scaled score: 0.9936545604622369

RandomForestClassifier unscaled score: 0.9914878250103177

RandomForestClassifier scaled score: 0.9914878250103177

### Conclusion

Scaling the data using Standard Scaler improved test prediction accuracy by nearly 0.2 basis points for the logistic regression model ( 0.9918489475856377 to 0.9936545604622369), but there was any noticeable improvement for the random forest classifier when scaling data with StandardScaler It's surprising, but LogisticRegression with data scaled using StandardScaler performed better than any of the other 3 models with an accuracy of 0.9936545604622369.

<hr>
Contact : 

* tourteau.christian@gmail.com
* https://www.linkedin.com/in/christian-tourteau/
