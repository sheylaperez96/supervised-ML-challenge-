# Unit 19 Homework: Predicting Credit Risk

In this assignment, I will be building a machine learning model that attempts to predict whether a loan will be approved or not. I will be using the [lending data](Resources/lending_data.csv) to create two machine learning models to classify the risk level of given loans. Specifically, I will be comparing a Logistic Regression model and Random Forest Classifier model.

<hr>

### **Part 1**: Making a Prediction
My prediction is that the logistic regression model will perform better than the random forest model. The purpose of this model is to help others make a decision (is this a risky loan?), and logistic regression models are very suitable for binary classification. Furthermore, there are not that many dependent variables (7) and all of the variables are numerical, so logistic regression is a good match for the data.

<hr>

### **Part 2**: Scoring the Models
Below are the different test scores for both models:
- Logistic Regression Training Score: 0.9924680148576145
- Random Forest Training Score: 0.9921584812216261

Based on these results, the logistic regression model performs slightly better, but the difference is negigible. It looks like both models perform very well on the data. If I had to choose a model, I would go with logistic regression since it is easier to interpret and explain, and it also runs faster than Random Forest.
