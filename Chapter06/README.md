# Exercise
## 1 
What is the approximate depth of a Decision Tree trained(without restrictions) on a training set with 
1 million instance?

$log_2(10^2)=23$

## 2 
Is node's Gini impurity generally lower or greater than its parent's? It is generally lower/greater, or always lower/greater?

*generally* lower than parent's

## 3 
If a Decision Tree is overfitting the training set, is it good idea to try decresing max\_depth?

Yes

## 4 
If a Decision Tree is underfitting the training set, is it good idea to try scaling the input features?

No

## 5
If it take one hour to train a Decision tree on the training set containing 1 million instances. roughly how much time will it take to train another Decision Tree on a training set contain 10 million instances?

$O(n \times mlog(m)$, it will take $\frac{10mlog(10m)}{mlog(m)}$ hours.

## 6 
If your training set contains 100,000 instances, will setting presort=True speed up the training?

No

## 7 & 8
See Exercise.ipynb