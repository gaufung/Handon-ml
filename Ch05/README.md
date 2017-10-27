# Exercise

## 1 
What is the fundamental idea bedind Support Vector Machine

*Answer*
fit the widest possible "street" between the classes.

## 2 
What's a support Vector

*Answer*
any instance located on the "stree", including the border.

## 3 
why is it important to scale the input when using SVMs

*Answer*
The small features will be neglected.

## 4 
Can an SVM Classifier output a confidence score when it classifiers an instance? what about a probability?

*Answer*
SVM can calculate the distance between the test instance and the decision boundary. But it cannot be directly
convert into an estimation of class probability.

## 5 
Should you use the primal or dual form of the SVM problem to train a model on the training
set with millions of instance and hundred features?

*Answer*
kernel trick can only use the dual form. if you have millions of instances, you had better choose
the primal form.

## 6
Say you train an SVM classifier with an RBF kerenl. It seems to underfit the training set: should you 
increase or decrease gamma? What about about C?

*Answer*
increase gamma or C (or both)

## 7
How should you set the QP Parameter(H, f, A and b) to slove the soft margin linear SVM classifier problem using an off-the-shlef QP slover?


## 9 & 10
See Exercise.ipynb