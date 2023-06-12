# Errata, Corrections and Improvements
----------------------------------------------------
If you find any mistakes in this Book, Machine Learning with R Fourth Edition, or if you have suggestions for improvements, then please [raise an issue in this repository](https://github.com/PacktPublishing/Machine-Learning-with-R-Fourth-Edition/issues), or email to us.

## Chapter04, Correcting a typo error from `naiveBayes` to `naive_bayes`
On page 142 in *Step 3 - training a model on the data*,
`sms_classifier <- naiveBayes(sms_train, sms_train_labels)`
should be writted as 
`sms_classifier <- naive_bayes(sms_train, sms_train_labels)`

On page 144 in *Step 5 - improving model performance*,
`> sms_classifier2 <- naiveBayes(sms_train, sms_train_labels, laplace = 1)` should be written as `> sms_classifier2 <- naive_bayes(sms_train, sms_train_labels,
laplace = 1)`
