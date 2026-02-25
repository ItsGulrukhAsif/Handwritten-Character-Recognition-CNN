**Handwritten Digit Recognition using CNN**
**Project Overview**

This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits using the MNIST dataset. The model is trained using TensorFlow and Keras and achieves approximately 99% accuracy on the test dataset.

**Dataset**

The dataset used in this project is the MNIST dataset.

MNIST is a benchmark dataset in computer vision and deep learning, containing:

60,000 training images

10,000 testing images

Grayscale images of size 28x28 pixels

Labels from 0 to 9 representing handwritten digits

The dataset was directly loaded using:

_keras.datasets.mnist.load_data()_

Each image has a corresponding labeled digit, making this a supervised classification problem.

**Technologies Used**

Python

TensorFlow / Keras

NumPy

Matplotlib

Seaborn

Google Colab (with Tesla T4 GPU)

**Model Architecture**

The CNN architecture includes:

Conv2D layer (32 filters)

MaxPooling layer

Conv2D layer (64 filters)

MaxPooling layer

Flatten layer

Dense layer (128 neurons)

Output layer (Softmax activation)

**Model Performance**

Training Accuracy: ~99.5%

Validation Accuracy: ~99%

Loss Function: Sparse Categorical Crossentropy

Optimizer: Adam

Evaluation: Confusion Matrix and Accuracy Curves

**Future Improvements**

Extend to EMNIST dataset for alphabet recognition

Implement CRNN for full word recognition

Deploy as a web application using Flask or Streamlit

**Author**

Gulrukh Asif
Artificial Intelligence Student
