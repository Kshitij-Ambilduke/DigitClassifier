# DigitClassifier

This repository is the implementation of Digit Classifier on MNIST dataset from scratch. <br/>
The whole multi-class classification was done using only NumPy library from scratch without using any frameworks. This classification task was done using a DNN (Dense neural network) which takes input the pixels of the image that is to be classified and learns a function to map each image to a label which is one among the 10 digits (0 to 9).
The model was trained using gradient descent and an accuracy of 92.1% was noted after 100 updates. <br/>
The model architecture is as follows : 
```
layer1 = Linear layer (input_features = 784, output_features = 500)
layer2 = Linear layer (input_features = 500, output_features = 100)
layer1 = Linear layer (input_features = 100, output_features = 10)
```
Along with these linear layers, ReLU (rectified linear unit) non-linearity was used. The final loss that was recorded was 0.271 (cross-entropy loss).<br/>
<br/>
The Parameters of this network were saved in case of future use and are attached in this repository itself.
