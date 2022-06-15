# Simple neural network
a.
1) Run the code of 2 layer neural network from <br/>
2) https://stackabuse.com/creating-a-neural-network-from-scratch-in-python-adding-hidden-layers/<br/>
3) Go through the code and understand each line.<br/>
4) Read the dataset as shown there.<br/>
5) Two classes are there. Label 0 for one class, 1 for another class<br/>
6) Take 70% data for training. 30% data for testing<br/>
7) Build a two-layer neural network from from scratch where zo is the output.<br/>
   a) You will have two layers.<br/>
       i) One is hidden layers ( use 4 neurons)<br/>
       ii) One output layer (use one output neuron)<br/>
   b) Use sigmoid function as activation function in each neuron.<br/>
   c) Use sum of square error as your loss function.<br/>
   d) Calculate the derivatives for back propagation.<br/>
8) Write codes training module for 2000 epochs to train the neural network.<br/>
9) Now classify the test data using the trained neural network.<br/>
   a) During the test, you will do only forward pass.<br/>
   b) If the forward pass score is , make the class label 1. Otherwise 0.<br/>
   c) Report your accuracy.<br/>
10) Draw data points for training data and also plot the class boundary in 3D plot<br/>
11) Draw data points for test data and also plot the class boundary in 3D plot<br/>
12) You cannot use any built-in deep learning functions<br/>

b (same as a. But the input is 3X32X32 image instead of 3 numbers.<br/>
1)  Select any two classes from CIFAR 10 dataset. For example: Airplane, cat.<br/>
2)  So, airplane means numerical label 0, cat means 1<br/>
3)  Now, read one image, reshape it to row vector x. x is our input data now with dimension 1X3072. <br/>
4)  x's class label would be either 0 or 1.<br/>
5)  Now implement the same network architecture as above.<br/>
6)  Build a two-layer neural network from scratch where Y_pred is the output.<br/>
    ➢   You will have two layers.<br/>
        •  One is hidden layers ( use 1000 neurons)<br/>
        •  One output layer (use one output neuron)<br/>
    ➢   Use sigmoid function as activation function in each neuron.<br/>
    ➢   Use sum of square error as your loss function.<br/>
    ➢   Calculate the derivatives for back propagation.<br/>
7)  Write codes training module for 10 epochs to train the neural network.<br/>
8)  Then, use the test images of airplane and cats from the test set.<br/>
9)  Supply the test images to the trained neural network and classify the images by using the Y_pred <br/>
   as follows<br/>
   ➢   If (y_pred < 0.5) then class label is 0 else class label is 1.<br/>
10)  Report your accuracy on the test set<br/>
