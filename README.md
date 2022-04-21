# Fashion-autoencoder
Developed in the Neural Networks course by: Diego Quezada and Kevin Reyes.
## Objectives
- Obtain low dimensional representations of clothing images using Autoencoders.
- Identify similar classes that could be conflicting for the model.
- Evaluate the effect of the depth of the autoencoder in the reconstruction of the initial image.
- Compare autoencoder with fully connected neural network architecture and convolutional autoencoder.
- Use autoencoder to remove noise from the data.
- Generate images of clothes using an autoencoder.

## Description
Analysis of use cases of Autoencoders in images of clothing.

## Conclusions
- The convolutional autoencoder architecture has much better results than the autoencoder with a fully connected network.
- Using a convolutional autoencoder it is possible to represent the highest level information (edges) in a lower dimensionality.
- The autoencoder denoising manages to clean an image with white noise, however, it only preserves edge information and some color changes in the image.
- The generated images only have some silhouettes similar to clothes, however the result is poor.

## Technology stack
- Tensorflow.
- Keras.
- Numpy.
- Matplotlib.