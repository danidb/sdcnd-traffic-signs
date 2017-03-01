# Traffic-Sign Classification with Deep Convolutional Neural Networks

The main objective of this work is personal scholarship - experimentation with novel neural network architectures, and studying approaches to similar problems applied by other authors. Traffic Sign classification is by no means a new problem, and here it is an academic exercise.

## Overview
All sources related to this work are contained in the iPython notebook `Trafic_Sign_Classifier.ipynb`. The neural network built here is based on the inception architecture, and a number of known approaches to traffic sign classification. The notebook contains extensive detail. For a quick overview of the network architecture, see the diagram in `signception_diagram.png`.

### Development Machine
These sources depend on TensorFlow (GPU distribution), OpenCV, Matplotlib, Numpy and Scipy. Development and testing was carried out on a MacBook Pro 11'3 with an nVidia 750M GPU, running Python 3.5.2 and Anaconda 4.2.0.

### Data
The data used for training, validation, and testing of the model is part of the German Traffic Sign Recognition Benchmark (GTSRB) database. For economy of space, the training and testing data is not included in this repository.