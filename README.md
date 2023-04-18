# Python Neural Network

## 👋 Description
This is a simple implementation of a neural network in Python. You can think of it as a translation of 3Blue1Brown's 4-part series on neural networks into computer code.

There are many libraries and projects out there for optimized machine learning. This project is about the human learning of machine learning. The code is straightforward and hopefully well organized. I attempted to make it as easy to follow and understand as possible. Every operation is broken up into discrete methods with descriptive names and inner workings that should be able to be understood if examined.

As a companion to the 3Blue1Brown series, I recommend watching that first or with this code open to see if you can follow along with his explanations in this code.

## 📦 Dependancies
```pip install pickle```

## 🚀 Use
If you simply run the neural_network.py script it will make a neural network of shape [784, 16, 16, 10] and train itself on the mnist training data for 5 minutes. It will print out a progress report on the console every 10 seconds and a final report at the end of the 5 minutes. The reports will include the accuracy of the predictions and the mean squared error measurement of loss.
Try different network shapes by changing the shape peramater in the init method of the NeuralNetwork class.
Try out different learning rates, batch sizes, and training times as arguments in the train_network method.
Save and load models by supplying a name to the neural_network class on instantiation to load and a name as an additional paramater of the train_network method to save.
I included a script for how I formatted and packaged the raw mnist data. I recommend just using the provided pickle but the script is there if you want to prepare the data yourself. 
