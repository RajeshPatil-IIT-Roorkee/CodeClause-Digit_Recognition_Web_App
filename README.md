# CodeClause-Digit_Recognition_Web_App
Hand Written Digit Recognition Web App by using CNN


Welcome to the Digit Recognition Web App repository! This project is a simple yet powerful web application that harnesses the capabilities of a Convolutional Neural Network (CNN) trained on the MNIST dataset to recognize handwritten digits. The app is meticulously crafted using Keras, TensorFlow.js, HTML, CSS, and JavaScript, and it proudly resides on GitHub Pages.

Project Structure
The architecture of the app is designed with clarity and efficiency in mind:

Keras: The CNN model is meticulously built and trained using the versatile Keras library.
Tensorflow.js: The trained model undergoes a transformation, emerging as a JSON file for architecture and an H5 file for weights, thanks to the prowess of TensorFlow.js converters.
HTML + CSS + JavaScript: The frontend of the web app is brought to life through the perfect synergy of these essential web technologies.
GitHub Pages: The web app finds its home on GitHub Pages, ensuring easy and accessible deployment.
Hello World of Object Recognition!
This project stands as a beacon, illustrating the "Hello World" example for object recognition, with a specific focus on deciphering the nuances of handwritten digits.

Aim
At its core, the primary objective of this project is to birth a CNN model with the innate ability to recognize handwritten digits. The training ground for this digital maestro is none other than the MNIST dataset, a staple in the world of image recognition within the realms of Keras.

MNIST Dataset
Delving into the depths of the MNIST dataset reveals a trove of 60,000 training images and 10,000 testing images, each a grayscale masterpiece spanning 28x28 pixels.

CNN Model Overview
A majestic 17-layer model, a symphony of Conv2D, MaxPooling2D, BatchNormalization, Dense, Flatten, and Dropout layers.
The input layer gracefully houses 32 neurons, while the output layer stands proud with 10 neurons, each representing a distinct digit class.
With 30 epochs as its crucible, the model undergoes training with Categorical Cross-Entropy as its guide, and Adam as the optimizer.
The culmination of this symphony is an awe-inspiring accuracy rate of 99.15%.
Deployment
Embarking on the deployment journey:

Save the model with TensorFlow.js converters, manifesting as a JSON file for architecture and an H5 file for weights.
Employ the wizardry of TensorFlow.js to seamlessly load the model and unleash its predictive prowess within the realms of JavaScript.
Feel free to navigate the code, contribute your insights, and be part of the magic. If queries or suggestions spark within you, don't hesitate to open an issue. Thank you for gracing the Digit Recognition Web App with your presence! 🚀✨
