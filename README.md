# Simple neural network
a.
1) Run the code of 2 layer neural network from
2) https://stackabuse.com/creating-a-neural-network-from-scratch-in-python-adding-hidden-layers/
3) Go through the code and understand each line.
4) Read the dataset as shown there.
5) Two classes are there. Label 0 for one class, 1 for another class
6) Take 70% data for training. 30% data for testing
7) Build a two-layer neural network from from scratch where zo is the output.
   a) You will have two layers.
       i) One is hidden layers ( use 4 neurons)
       ii) One output layer (use one output neuron)
   b) Use sigmoid function as activation function in each neuron.
   c) Use sum of square error as your loss function.
   d) Calculate the derivatives for back propagation.
8) Write codes training module for 2000 epochs to train the neural network.
9) Now classify the test data using the trained neural network.
   a) During the test, you will do only forward pass.
   b) If the forward pass score is , make the class label 1. Otherwise 0.
   c) Report your accuracy.
10) Draw data points for training data and also plot the class boundary in 3D plot
11) Draw data points for test data and also plot the class boundary in 3D plot
12) You cannot use any built-in deep learning functions

b (same as a. But the input is 3X32X32 image instead of 3 numbers.
1)  Select any two classes from CIFAR 10 dataset. For example: Airplane, cat.
2)  So, airplane means numerical label 0, cat means 1
3)  Now, read one image, reshape it to row vector x. x is our input data now with dimension 1X3072. 
4)  x's class label would be either 0 or 1.
5)  Now implement the same network architecture as above.
6)  Build a two-layer neural network from scratch where Y_pred is the output.
    ➢   You will have two layers.
        •  One is hidden layers ( use 1000 neurons)
        •  One output layer (use one output neuron)
    ➢   Use sigmoid function as activation function in each neuron.
    ➢   Use sum of square error as your loss function.
    ➢   Calculate the derivatives for back propagation.
7)  Write codes training module for 10 epochs to train the neural network.
8)  Then, use the test images of airplane and cats from the test set.
9)  Supply the test images to the trained neural network and classify the images by using the Y_pred 
   as follows
   ➢   If (y_pred < 0.5) then class label is 0 else class label is 1.
10)  Report your accuracy on the test set
