# CNN-classification-on-MNIST-dataset
This code is a Python script that demonstrates building, training, and evaluating a Convolutional Neural Network (CNN) using TensorFlow/Keras on the MNIST dataset, which consists of handwritten digit images.
Here's a summary of what the code does:
It loads the MNIST dataset which contains the training and test images along with their corresponding labels.
It normalizes the pixel values of the images to be between 0 and 1.
It builds a CNN model using TensorFlow/Keras with several Conv2D, MaxPooling2D, Dropout, Flatten, and Dense layers.
It compiles the model with the specified loss function, optimizer, and metrics.
It reshapes the training and test data to be compatible with the CNN architecture.
It trains the model on the training data for a specified number of epochs.
It evaluates the trained model on the test set and prints the test accuracy.
It makes predictions on the test set and displays the predictions for the first image in the test set.
It plots the model's training accuracy and loss over the epochs.
It defines functions to plot images, their predicted labels, and the probability distribution of predictions.
It plots a grid of test images, their predicted labels, and the true labels, highlighting correct and incorrect predictions.
Overall, this code showcases the process of building, training, and evaluating a CNN for handwritten digit classification using the MNIST dataset, and visualizing the results using plotlib.
