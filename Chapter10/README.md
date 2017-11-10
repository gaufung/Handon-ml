![](./ArtificialNeuralNetwork.png)

# Exercises

2. Why is it generally preferable to use a *Logistic Regression* classifier rather than a *Perception*? How can you tweak a Perception to make it equvalent to a Logistic Regression clasifier?

3. Why was the logistic activation function a key ingredient in training the first MLPs?

4. Name three popular activition functions. Can you draw them?

5. Suppose you have an MLP composed of one input layer with 10 passthrough neurons, followed by one hidden layer with 50 artifical neurons, and finally one output layer with 3 artificial neurons. All artificial neurons use the `ReLU` activation functions.

- What is the shape of input matrix **X**?

- What about the shape of hidden layer's weight vector **Wh**, and the shape of its bias vector **bh**?

- What is the shape of the network's output matrix **Y**？

- Write the equation that computes the network's output matrix **Y** as a function of **X**, **Wh**, **bh**,
**Wa** and **b0**.

6. How many neurons do you need in the output layer if you want to classify email into spam or ham? What activation function should you use in the output layer? If instead you want to tackle the MNIST, how many neurons do you need int the output layer, using what activation function? Answer the same questions for getting your network to predict housing prices as in Chapter 2?

7. What is backpropagation and how does it work? What is the difference between backpropagation and reverse-mode autodiff?

8. Can you list all the hyperparameters you can tweak in an MLP? If the MLP overfits the training data, how could you tweak thest hyperparameters to try to solve the problem?

