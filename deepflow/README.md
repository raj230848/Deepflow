
1. machine learning

 In the first step, I take data from Kaggle and apply machine learning models to it. Data is about the dropout of students after secondary education.


    link - https://www.kaggle.com/datasets/abdullah0a/student-dropout-analysis-and-prediction-dataset/code

 Analysis of why students dropped the schools and what are the main reasons behind that.

 used different ml models-

    1. Logistic regression
    2. Support vector machine
    3. Decision tree
    4. Naive Bayes classifier
    5. Random forest
    6. Bagging classifier
    7. Boosting:
          i.Adabost
          ii. Gradient boost
          iii.XGBoost classifier
    8. Extratree classifier

Since the data is imbalanced so I focused on maximizing the F1 score rather than focusing on accuracy.
Found that Decision tree based models are able to maximize the F1 score


2. Neural network implementation
   
   I.Logistic regression as a perceptron

       Implement single perceptron using the logistic regression
   
   II.Build single hidden layer neural network

       implement a 2-class classification neural network with a single hidden layer
       Use units with a non-linear activation function, such as tanh, ReLu
       Compute the cross-entropy loss
       Implement forward and backward propagation
   III. Building your Deep Neural Network

       implement forward propagation in multilayer
       compute cross-entropy loss
       implement backward propagation

   IV.Deep Neural Network for Image Classification

       Use the implemented model to classify cat v/s, not cat
   
3. Neural network optimization

 to optimize the performance of the neural network, there are some techniques-

 I. Weight initialization 

     to get rid of the vanishing gradient problem
     1. Xavier's initialization for Tanh activation function
     2. He initialization for Relu activation function
     
 II.Regularization

    to get rid of overfitting, we use regularisation
     1.L1 regularization
     2.L2 regularization

     here I implement L2 regularization with binary cross entropy loss function and  reduce the loss 
     how backpropagation works with  regularization

 III.Gradient Checking

     Check whether the calculated gradient is correct or not so that weights update properly.
     
IV.Optimizer 

    role of optimizer becomes more crucial when working with large data, then we want fast computation and less training time For that we have different optimizers
     Here I  implement different optimizers from the sketch
       1. Mini batch gradient descent
       2. momentum
       3. Adam
       
  
 
