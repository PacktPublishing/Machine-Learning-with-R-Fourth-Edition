# Errata, Corrections and Improvements
----------------------------------------------------
If you find any mistakes in this Book, Machine Learning with R Fourth Edition, or if you have suggestions for improvements, then please [raise an issue in this repository](https://github.com/PacktPublishing/Machine-Learning-with-R-Fourth-Edition/issues), or email to us.

## Chapter 04, Correcting a typo error from `naiveBayes` to `naive_bayes`
On page 142 in *Step 3 - training a model on the data*:
`sms_classifier <- naiveBayes(sms_train, sms_train_labels)`
should be written as 
`sms_classifier <- naive_bayes(sms_train, sms_train_labels)`

On page 144 in *Step 5 - improving model performance*:
`> sms_classifier2 <- naiveBayes(sms_train, sms_train_labels, laplace = 1)`
should be written as
`> sms_classifier2 <- naive_bayes(sms_train, sms_train_labels, laplace = 1)`

## Chapter 06, Adding missing parentheses in the logistic regression modeling syntax box
On page 241, in the logistic regression syntax box *building the model* section:
`m <- glm(dv ~ iv, data = mydata, family = binomial(link = "logit")`
should be written as:
`m <- glm(dv ~ iv, data = mydata, family = binomial(link = "logit"))`

Also on page 241, in the logistic regression syntax box *making predictions* section:
`churn_model <- glm(churn ~ ., data = churn_data, family = binomial(link = "logit")`
should be written as:
`churn_model <- glm(churn ~ ., data = churn_data, family = binomial(link = "logit"))`

## Chapter 14, Correcting typos in `caret` output explanations
On page 603, the accuracy estimate of 72.996 percent should be changed to 72.705 perecent to align with the optimal model that had `trials = 20`, `model = tree` and `winnow = FALSE`. Consequently, the text "which can be found in the last row of section three" should be changed to "which can be found in the third row of section three."

Similarly, on page 608, the best model according to the output used `trials = 5` and NOT `trials = 1` as suggested by the text. Therefore, the text "whereas here, it used `trials = 1`" should be changed to "whereas here, it used `trials = 5`" and the line "the single-trial model offers reasonably close performance" should be changed to "the five-trial model offers reasonably close performance."
