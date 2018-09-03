# Cats_vs_Dogs

## Summary
Dataset contains 4000 images of cats and dogs in training set and 1000 images of cat and dogs in test set. Here **Convolutional Neural Net** is used for building model which predicts whether the image is of cat or dog.

The model is in the raw form and is not a end-to-end solution. User needs to build pipeline to use it in real time.

About the Model.
- **2 Convolutional Layers** followed by **max pooling** layers.
- Activation to fire the weith matrix : **ReLU**
- Activation function of output layer after flattening : **Sigmoid** (since only two classes are there. Hence 2 Dimentional Data)
- Softmax can be used for higer dimentional data.
