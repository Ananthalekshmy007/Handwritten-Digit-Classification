# Handwritten-Digit-Classification
Handwritten Digit Classification using CNN 
The core idea of this project is the basic implementation of Convolutional Neural Networks using Keras and training it to predict the input (handwritten digit) to the GUI.
The CNN is later linked with a GUI developed in Tkinter for the purpose of interaction. The GUI enables the user to provide the input as digits using the cursor and let it predict the digit along with its accuracy of prediction
With the mnist dataset is used for the training and testing. It consists of 60000 training images of the handwritten digits from 0 to 9 and almost 10000 images of the same for testing. 
The dataset is loaded and is processed in the necessary form and is passed to the convolution layers and the output is provided by the last layers (10 tensors – 1 for each digit). The trained model is then set to be tested with 10000 images and finally it is evaluated on the basis of the given input digits.
The project is set up in python and the libraries used include Keras (TensorFlow backend), NumPy, PIL, Tkinter, wingui. Since the model uses mnist dataset, the biases are set to none and with a considerable number of epochs, the model is having 99% prediction accuracy. The model has 8 convolution layers and the accuracy can be further increased by using more convolution layers. 
