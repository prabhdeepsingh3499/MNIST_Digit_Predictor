# MNIST_Digit_Predictor
The goal is to build a Neural Network which is able to predict the numbers in range of 1-9 using Python.
This is done using the following libraries- keras ( tensorflow in backend ). matplotlib ( for plotting and analysing the data ). numpy ( for mathematical calculations and normalising data ). warnings (To ignore warnings and make code readable ).

The data has been taken from Keras MNIST dataset. Explanation:

1. Loading the Libraries.

2. Loading the data and spliting it into Train and Test Data.

3. Analysing the Data
![EDA](https://github.com/prabhdeepsingh3499/MNIST_Digit_Predictor/blob/master/images/EDA.png?raw=True)
4. Normalizing the Data

5. Importing the Sequential Model and using Sequential Layers

6. Compiling the Model and Evaluating the Data

7. The Accuracy Score of Model is 95 %

![Result](https://github.com/prabhdeepsingh3499/MNIST_Digit_Predictor/blob/master/images/Result.png?raw=True)
 
8. The Neural Network looks like-

![Summary](https://github.com/prabhdeepsingh3499/MNIST_Digit_Predictor/blob/master/images/Model.png?raw=True)

The activation function used in last layer is Softmax, as it gives the probability of the prediction, the label that gives maximum probability is selected as the label.

In order to get better accuracy you can tweak the neural network and accordingly change the layers.
