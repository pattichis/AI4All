# Basic terms
1. DATA = 2-dimensional points.
3. INPUTS = FEATURES = One-dimensional X1 and X2. Others are two-dimensional.
4. Neurons multiply their inputs and add a bias. Line thickness = weight.
5. OUTPUT = COLOR overlaid over training and testing data.
6. Noise is a random change to the DATA. Note that it changes both training and testing datasets.

# Setup
Right-click to open [Neural Networks Playground Website in a separate window](https://playground.tensorflow.org/).
Place the windows side-by-side to continue with the instructions.

# Basic Training
1. Hit the reset button (arrow turning back left) or reload the website.
2. Note the colors of the output points. They represent different classes.
3. Look at the background color. They represent what the untrained neural network predicts the colors should be. They are NOT correct yet.
4. Click the Play button.
5. Can you see the training and testing loss graphs getting reduced?
6. Did the colors get corrected? How do you know?

# What to observe during training (after you click play):
1. Neuron outputs: Hover over each neuron (do not click on it). Look at the output. What is the relationship between the input features and the output?
2. Connection thickness refers to the weight strength.
3. Note that the output plot represents the output from the final neuron. 
4. Training versus testing losses: Watch the train loss and test loss curves. What are the minimum values? What is the distance between them? You want both of them low. Overfitting: Test loss is high. Train loss is low. Reduce the network. Underfitting: High losses. Enlarge the network.
5. Watch the output colors evolve over time. This is what the neural network is learning. What is the relationship to the plotted points?
6. Click on "Show test data" on the lower-right. What is the relationship between the training and testing datasets? Are they representative of each other?
7. Click and unclick on "Show test data". The correct output is presented for Noise=0. The small dots represent the training data. The large dots represent the testing data. 
 
# Train on X1 only
1. Click on any input to select or deselect it.
2. Make sure no connections are leaving any other input.
3. Train on X1 alone.
4. Why did this not work?
5. Can you think of the clinical implications of not having enough variables in a real-world example?

# Suggested experiments for concentric dataset (upper-left)
##  Add a little noise to the data.
1. Maximize the number of layers and the number of neurons in each layer. Is this overfitting?
2. Minimize the number of layers and the number of neurons in each layer. Why is this underfitting?
3. Run on all of the features. Can you see artifacts? Remove features and rerun.
4. Reduce the ratio of training to test dataset. What is enough?
5. Modify the noise. How does it change performance?
6. Experiment with the number of features while keeping the same network. 

# Rerun the experiments using the spiral dataset (lower-right)
1. This is a much more difficult dataset! What can you say about the final output compared to before?
2. What should we do to the network for this problem? Increase? Decrease? Why?
3. How sensitive is the training to the percentage of training to testing samples? Why?
