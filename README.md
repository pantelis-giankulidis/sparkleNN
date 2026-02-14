## Sparkle NN ##
This library provides simple implementation blocks , suitable for creating and training artificial neural networks in python. There are four buliding blocks provided: 
* Value \
Represents a simple value. It provides functionality for interaction with other values, like add, subtract, backpropagate values etc. 
* Neuron \
Represents a neuron in the network. It contains an array of Value , representing the weights of the neuron. The number of inputs is it's only parameter. 
* Layer \
Represents a layer in the network. It contains an array of Neuron, representing the neurons of the layer. The parameters it takes are the input size of the neurons and their quantity.
* MLP \
Represents an entire network. It contains an array of Layer, representing the layers of the network. The parameters are the number of layers and their input sizes. 

### Installation
Install the library with `poetry add sparklenn` for poetry, or `pip install sparklenn` for Pypi. It can be imported in your python project as a regular library

### Example
In the file example.py is provided a very simple implementation of a neural network of three layers with 4, 4 and 1 neurons each. The network is trained with dummy data, using the LSE loss function.
