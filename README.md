# CodeClause-Digit_Recognition_Web_App
Hand Written Digit Recognition Web App by using CNN
Welcome to the Digit Recognition Web App repository! This project is a simple web application that utilizes a Convolutional Neural Network (CNN) trained on the MNIST dataset to recognize handwritten digits. The app is built using Keras, TensorFlow.js, HTML, CSS, and JavaScript, and it is hosted on GitHub Pages.

Project Structure
The structure of the app is as follows:

Keras: The CNN model is built and trained using the Keras library.
Tensorflow.js: The trained model is converted to a JSON file for architecture and an H5 file for weights using TensorFlow.js converters.
HTML + CSS + JavaScript: The front-end of the web app is implemented using these technologies.
GitHub Pages: The web app is hosted on GitHub Pages for easy access.
Hello World of Object Recognition!
This project serves as a "Hello World" example for object recognition, focusing on handwritten digits.

Aim
The primary goal of this project is to create a CNN model capable of recognizing handwritten digits. The model is trained on the MNIST dataset available in Keras.

MNIST Dataset
The MNIST dataset consists of 60,000 training images and 10,000 testing images. Each image is 28x28 pixels in grayscale.

CNN Model Overview
It is a 17-layer model with a combination of Conv2D, MaxPooling2D, BatchNormalization, Dense, Flatten, and Dropout layers.
The input layer has 32 neurons, and the output layer has 10 neurons representing the 10 different digit classes.
30 epochs are used for training.
Categorical cross-entropy is the loss function, and Adam is used for optimization.
The model achieves an impressive accuracy of 99.15%.
Deployment
To deploy the model:

Save the model using TensorFlow.js converters, generating a JSON file for the architecture and an H5 file for the weights.
Use TensorFlow.js to load the model and make predictions in the JavaScript file.
Feel free to explore the code and contribute to the project. If you have any questions or suggestions, please open an issue. Thank you for checking out the Digit Recognition Web App!
