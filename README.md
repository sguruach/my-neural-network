# my-neural-network

My attempt at creating a basic neural network from scratch! 

Artificial neural network architecture:

1. input layer = 64 neurons (input image array)

2. hidden layer 1 = 10 neurons (arbitrary)
   
3. hidden layer 2 = 10 neurons (arbitrary)

4. output layer = 10 neurons (output one-hot array)

5. sigmoidal activation in the two hidden layers

6. softmax activation in the output layer

7. cost function = cross-entropy

8. learning rate = 2

9. epochs = 1500

The neural network has been trained to recognize the MNIST data as provided by sklearn module. 

Data characteristics:

1. Data = MNIST handwritten digit data from sklearn. 

2. Size of each input = 64 (8-by-8 grey scale image)

3. Number of inputs = 1617

4. Size of output = 10 (digits {0,1,2,...,9})

5. Number of outputs = 1617

    
You can play around by changing the number of neurons in the hidden layers, learning rate and the number of epochs. You can also change the data to be trained on, e.g. use Fisher's iris dataset.
    
My reference:
- https://towardsdatascience.com/neural-networks-from-scratch-easy-vs-hard-b26ddc2e89c7
- http://neuralnetworksanddeeplearning.com/chap3.html
