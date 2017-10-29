![](./EnsembleLearning.png)


# Exercise

## 1 
If you have trained five differnet models on the extra same data, and they all achive 95% precision, is there any chance that you combine these models to get a better results? If so, how? If not, why?

Yes, if your models are different types, such as (SVM, Logistic Regression or Forests).

## 2
What is the different between hard and soft voting?

- hard voting
majority voting  
- soft voting
voting by the average probabilities of each class



## 3
Is it posssible to speed up training of bagging ensemble by distributing it across multiple servers?
what about pasting ensembles, boosting ensembles, random forests, or stacking ensemble?

- bagging: Yes
- pasting: Yes
- boosting: No
- random forest: Yes
- stacking ensemble: Yes


## 4
What is the benefit of out-of-bag evaluation?

Using instances that is not trained on, those can be treated as validation set.

## 5
What make Extra-Trees more random than regular Random Forest? How can this extra randomness help? Are Extra-Tree slower or faster than regular Random Forest?

- like regularzaion
- train faster

## 6 
If your AdaBoost ensemble underfit the training data, what hyperparameters should you tweak and how?

- add estimators
- increase learning rate

## 7 
If your Gradient Boosting ensemble overfits the training set, should you increase or decrese the learning rate?

decrease learning rate