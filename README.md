build a neural network using TensorFlow to classify handwritten digits
Explanation:

Data Loading and Preprocessing: We load the MNIST dataset, which contains images of handwritten digits. The images are normalized to a scale of 0 to 1 and reshaped into a 2D array.

Model Architecture: We create a simple neural network with two layers: a fully connected layer with 128 neurons and a ReLU activation function, and an output layer with 10 neurons (one for each digit) and a softmax activation function.

Model Compilation: We compile the model with the Adam optimizer, sparse categorical crossentropy loss, and accuracy metric.

Model Training: We train the model on the training data for 5 epochs.

Model Evaluation: We evaluate the model on the test data to assess its performance.
