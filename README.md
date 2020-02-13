# cs231n
[CS231N](http://cs231n.stanford.edu/2019/syllabus.html) Stanford University programming assignments

## Installation
```bash
conda create -n cs231n python=3 anaconda
conda activate cs231n
```
### Assignment 1
```
cd assignment1
./install_packages.sh
cd cs231n/datasets
./get_datasets.sh
```
- Q1: k-Nearest Neighbor classifier

  The IPython Notebook [knn.ipynb](https://github.com/RuslanAgishev/cs231n/blob/master/assignment1/knn.ipynb)
  will walk you through implementing the kNN classifier.
  
- Q2: Training a Support Vector Machine

  The IPython Notebook [svm.ipynb](https://github.com/RuslanAgishev/cs231n/tree/master/assignment1/svm.ipynb)
  will walk you through implementing the SVM classifier.
  
- Q3: Implement a Softmax classifier

  The IPython Notebook [softmax.ipynb](https://github.com/RuslanAgishev/cs231n/tree/master/assignment1/softmax.ipynb)
  will walk you through implementing the Softmax classifier.
  
- Q4: Two-Layer Neural Network

  The IPython Notebook [two_layer_net.ipynb](https://github.com/RuslanAgishev/cs231n/tree/master/assignment1/two_layer_net.ipynb)
  will walk you through the implementation of a two-layer neural network classifier.
  
- Q5: Higher Level Representations: Image Features
  The IPython Notebook [features.ipynb](https://github.com/RuslanAgishev/cs231n/tree/master/assignment1/features.ipynb)
  will walk you through this exercise, in which you will examine the improvements gained
  by    using higher-level representations as opposed to using raw pixel values.


### Assignmnet 2
```
cd assignment2
./install_packages.sh
cd cs231n/datasets
./get_datasets.sh
```

- Q1: Fully-connected Neural Network
  The IPython notebook [FullyConnectedNets.ipynb](https://github.com/RuslanAgishev/cs231n/blob/master/assignment2/FullyConnectedNets.ipynb)
  will introduce you to our modular layer design, and then use those layers to
  implement fully-connected networks of arbitrary depth. To optimize these models you will implement several popular update
  rules.
  
- Q2: Batch Normalization
  In the IPython notebook [BatchNormalization.ipynb](https://github.com/RuslanAgishev/cs231n/blob/master/assignment2/BatchNormalization.ipynb)
  you will implement batch normalization, and use it to train deep fully-connected networks.

- Q3: Dropout
The IPython notebook [Dropout.ipynb](https://github.com/RuslanAgishev/cs231n/blob/master/assignment2/Dropout.ipynb) will help you implement Dropout and explore its effects on model generalization.

- Q4: Convolutional Networks
In the IPython Notebook [ConvolutionalNetworks.ipynb](https://github.com/RuslanAgishev/cs231n/blob/master/assignment2/ConvolutionalNetworks.ipynb) you will implement several new layers that are commonly used in convolutional networks.
