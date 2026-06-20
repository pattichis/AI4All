# Step 0. Setup
Right-click to open [Neural Networks Playground Website in a separate window](https://playground.tensorflow.org/).
Place the windows side-by-side to continue with the instructions.

# Step 1. Select dataset
1. Upper-right corner: Make sure that the `Problem Type` is set to `Classification`.
2. Leftmost column: Under `DATA`, select any one of the four datasets:
   - Concentric Circles: two concentric circles (upper left).
   - Squares: four squares (upper right).
   - Circles: two circles (lower left).
   - Spirals: two spirals (lower right).

# Step 2. Select input features
1. You can click to select inputs to map to different outputs.
2. Your input features are:
   - X<sub>1</sub> acts like x, the horizontal axis.
   - X<sub>2</sub> acts like y, the vertical axis.
   - X<sub>1</sub><sup>2</sup> acts like x<sup>2</sup>.
   - X<sub>1</sub> X<sub>2</sub> acts like x y.
   - `sin`( X<sub>1</sub> ) acts like `sin(x)`.
   - `sin`( X<sub>2</sub> ) acts like `sin(y)`.

# Step 3. Create Neural Network Architecture
1. Click on `+ - HIDDEN LAYERS` (top center) to set up the number of hidden layers.
2. Click on `+ - neurons` above each layer to set up the number of neurons in each layer.
3. Click on `Activation` to select how to process the output.

# Step 4. Training
1. Hit the reset button (arrow turning back left) or reload the website.
2. Note the colors of the output points. They represent different classes.
3. Look at the background color. They represent what the untrained neural network predicts the colors should be. They are NOT correct yet.
5. Click the Play button.

# Step 5. What to observe during training (after you click play):
1. Note that the output plot represents the output from the final neuron. Compare this against each dataset. Discuss.
2. Can you see the training and testing loss graphs getting reduced? How?
3. Did the colors get corrected? How do you know?
4. Neuron outputs: Hover over each neuron (do not click on it). Look at the output. What is the relationship between the input features and the output?
5. Connection thickness refers to the weight strength. Can you verify?
6. Training versus testing losses: Watch the train loss and test loss curves. What are the minimum values? What is the distance between them? You want both of them low. Overfitting: Test loss is high. Train loss is low. Reduce the network. Underfitting: High losses. Enlarge the network.
7. Watch the output colors evolve over time. This is what the neural network is learning. What is the relationship to the plotted points?
8. Click on "Show test data" on the lower-right. What is the relationship between the training and testing datasets? Are they representative of each other?
9. Click and unclick on "Show test data". The correct output is presented for Noise=0. The small dots represent the training data. The large dots represent the testing data. 
 
