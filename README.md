# MNIST-and-CIFAR10-classification
MNIST data classification with feature visulization using keras-vis

Requirements: Keras DL framework.

1. Classify MNIST and CIFAR10 Dataset using deep convolutional neural network and visulazie features from different layers. 
Visulazied features are saved on "mnist_new_design_nov12"	and "output_cifar10" folders.

MNIST Dataset:
mnist_mydesign.py

CIFAR 10 dataset:
cifar_10_mydesign.py

2. Used trained resnet-152 weights on imagenet dataset to perform transfer learning. 
Then, SVM is used to classify the new representation of CIFAR 10 dataset.  

step 01: resnet152_cifar10_transfer_learning.py
step 02: SVM_fine_tuned_transfer_learning.m

for resnet-50 transfer leanring:
classification_using_svm_cifar10.m

