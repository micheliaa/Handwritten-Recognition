# Handwritten-Recognition

**Dataset**

The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.

It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting.

Four files are available on this site:

train-images-idx3-ubyte.gz:  training set images (9912422 bytes)
train-labels-idx1-ubyte.gz:  training set labels (28881 bytes)
t10k-images-idx3-ubyte.gz:   test set images (1648877 bytes)
t10k-labels-idx1-ubyte.gz:   test set labels (4542 bytes) 

**MNIST Dataset Reading**

Download the MNIST dataset directly from the official TensorFlow website and decompress it

In the MNIST dataset, the image are a tensor in the shape of [60000, 28, 28]. The first dimension is used to extract images, and the second and thirs dimensions are used to extract pixels in each image.

**CNN Construction**

The conventional CNN construction method helps you better to understand the internal network structure but has a large code volume.
Therefore attempts to construct a CNN by using high-level APIs are made to simplify the network construction process.
