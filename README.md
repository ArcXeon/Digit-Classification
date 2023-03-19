# Digit-Classification-Neural-Network  

The Digit Classification Project implements two deep neural networks for image classification on the MNIST dataset. The first network (Model 1) uses the sigmoid activation function in all layers, while the second network (Model 2) uses the rectified linear unit (ReLU) activation function in all layers except the output layer, which uses sigmoid.  

The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0-9), with 60,000 images for training and 10,000 images for testing. The code loads the data, normalizes the feature values, and converts the labels from integer to vector form.  

Both models have 10 hidden layers, with each layer containing 10 neurons. Batch normalization is used after each layer. The models are trained using the ADAM optimizer and categorical cross-entropy loss function. The code outputs the test accuracy for each model, which is the percentage of correctly classified images in the test set.  

After training the models, the code also predicts the label of a sample image from the test set using both models and displays the predicted digit.
