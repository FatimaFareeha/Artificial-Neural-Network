# Artificial-Neural-Network
## What is ANN?
An Artificial Neural Network or ANN is an information processing paradigm that is inspired by the way the biological nervous system, such as the brain, processes information. It is composed of large number of highly interconnected processing elements (neurons) working in unison to solve a specific problem.
The human brain is composed of 86 billion nerve cells called neurons. They are connected to other thousand cells by Axons. Stimuli from external environment or inputs from sensory organs are accepted by dendrites. These inputs create electric impulses, which quickly travel through the neural network. A neuron can then send the message to other neuron to handle the issue or does not send it forward. Similarly, taking inspiration from the biological precursor, ANNs are composed of multiple nodes, which imitate biological neurons of the human brain. The neurons are connected by links and they interact with each other. The nodes can take input data and perform simple operations on the data. The result of these operations is passed to other neurons. The output at each node is called its activation or node value.
Any Artificial Neural Network, irrespective of the style and logic of implementation, has a few basic characteristics:\
     • An Artificial Neural Network consists of large number of  “neuron” like processing elements.\
     • All these processing elements have a large number of weighted connections between them.\
     • The connections between the elements provide a distributed representation of data.\
     • A Learning Process is implemented to acquire knowledge.

### Advantages:
• ANN’s have the ability to learn and model non-linear and complex relationships.\
• It does not impose any restrictions on the input variables.\
• It is very good at handling highly volatile data which makes it a very useful tool in financial time series forecasting.
    
### Applications:
Originally, ANNs were used to solve problems the same way a human brain would. But over time, attention shifted and they were used to perform more specific tasks, such as:\
      • Image processing.\
      • Language processing.\
      • Speech recognition.\
      • Character recognition.\
      • Segmentation of image.\
      • Anomaly detection.\
      • Forecasting.

## About The Project
### Aim:
The main aim of this project is to help deploy a Python module that can be downloaded by users via pip, to create neural networks.

### How Does This Work?
Firstly, we feed some input data to the neural network.\
The data flows from layer to layer, until we get an output.\
After getting the output, we check for errors.\
Then, we can adjust the given parameter, weight or bias, by subtracting the derivative of the error.\
Finally, we repeat the process.

Two of the most important things in neural networking are: forward propagation and back propagation.\
We know that, the output of one layer acts as input for the next. This flow of data from one layer to another is called Forward Propagation.\
Backward Propagation, on the other hand, is the process in which the error is corrected in every iteration or epoch. This is possible when we find out the gradient at whcih error needs to be corrected.

Now, Gradient Descent is an algorithm that operates iteratively to find the optimal values for its parameters. It takes into account, user-defined learning rate, and initial parameter values.

![LEARNING RATE](https://user-images.githubusercontent.com/66374573/87868501-eb2ac880-c9b3-11ea-8a66-69ed27f746e1.png)

To add a non-linear element to this very liner calculation process, an Activation Function is used.

![ACTFUNC](https://user-images.githubusercontent.com/66374573/87868480-94bd8a00-c9b3-11ea-89cb-e4ae8ae18eed.png)

![ACTFUNCC](https://user-images.githubusercontent.com/66374573/87868601-47dab300-c9b5-11ea-945d-efb2794c1c5b.png)

Neural Network is an iterating algorithm (For example, in this project, epoch = 8000 i.e there are 8000 iterations). It is a whole cycle of reading data, learning from errors, updating the value until it reaches the desired value. When it comes to Artificial Intelligence, the longer a model is trained, the better we can yeild accurate results.

This projects helps serve this very purpose. It helps users download a Python Module (using pip), to create neural networks. It makes the user's job easy, while providing great precision and accuracy.

### Contribution Guidelines:
All sorts of contributions are welcome: bug reports, code submissions or pull requests, etc.
