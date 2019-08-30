# Deep_learning_digit_recognition_and_creation
A project to get familiar with Tensorflow and TensorBoard. How to artificially increase our dataset: rotation, zoom, contrast. Creating a generative auto-encoder to "dream" new digits.

The digit_creation.ipynb file contrain a fullyconnected autoencoder which is able to dream new digit (examples in the notebook and in the dedicated article on my website https://anthonypiquet.wordpress.com/2019/07/23/digit-recognition-and-clothing-classification/
(Note: my "transfer learning and unsupervised pre-training" repo contains a convolutional autoencoder)

The digit_recognition.ipynb file contains all the code to achieve 99.51% of accuracy to the MNIST digit recognition challenge using data augmentation, batch normalization, dropout and convolutional layers.
