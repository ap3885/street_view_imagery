# Digit Recognition from Street View Imagery using Convolutional Neural Networks

This is the final project for e4040 Neural Networks and Deep Learning Course - Digit Recognition from Street View Imagery using CNNs based on the paper Multi-digit Number Recognition from Street View Imagery using Deep Convolutional Neural Networks(https://arxiv.org/abs/1312.6082) by Ian Goodfellow et al.

Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Requirements

Python 3.6 with Jupyter Notebook

TensorFlow 1.13

Relevant version of Numpy

Relevant version of Matplotlib

Setup

Clone the source code
$ git clone https://github.com/cu-zk-courses-org/e4040-2019fall-project-mdnr-ap3885-as5697.git
Download the 'train_32x32.mat' and 'test_32x32.mat' from SVNH dataset( http://ufldl.stanford.edu/housenumbers/ )- Format 2

Extract to your local data folder in the same environment as the repo.

Code Layout

Our project is organized in three jupyter notebook files.

Preprocessing steps: Contains the code for preprocessing the downloaded data. Please run this first. This is a preprocessing step to create and save preprocessed data locally for training in the next two notebooks.

ConvNet : Code for importing data from previous step and training a standard ConvNet model on the cropped SVHN dataset

OurVersion : Code containing our network with 12 hidden layers to achieve higher accuracy.

Contributors

Ananye Pandey (ap3885@columbia.edu) UNI: ap3885

Apoorva Srinivasan (as5697@columbia.edu) UNI: as5697
