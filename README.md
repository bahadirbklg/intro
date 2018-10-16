# Introduction to Deep Learning for Medical Researchers
This repository contains a series of presentations, Google Colaboratory notebooks, and supporting code and provides an introduction to machine learning and deep learning tools and techniques. The material, created in collaboration with <a href="http://cetinkoc.net/">Prof. Çetin Kaya Koç</a>, was a short-course for medical researchers at İstinye University, Turkey. This class introduces basic and advanced techniques, with an emphasis on tools, model creation, and model validation.

The course is split into 12 one-hour modules. All computation is done on the cloud using free Google Colaboratory notebooks and free/open-source software: Python and PyTorch. Contents include:
1. Introduction
* Survey of recent medical applications  
* Artificial Intelligence, Machine Learning, Deep Learning: terminology and history
* Overview of the rest of the class
* Introduction to Google Colaboratory and Python

2. Introduction to supervised and unsupervised learning
* Intro to sci-kit learn
* Intro to Matplotlib
* Regression
* Classification
* Clustering

3. Supervised techniques
* Linear regression
* Linear disciminant analysis
* Random forests

4. Unsupervised techniques and confidence estimation #1
* K-Nearest Neighbors
* Precision, accuracy, recall: F-Score
* Confidence intervals
* Cross-validation

5. Confidence estimation #2
* Confusion matrices
* ROC curves
* Interpolation and extrapolation
* Curse of dimensionality 

6. Introduction to neural networks
* Linear vs. nonlinear functions
* The perceptron
* Multi-Layer Perceptron (MLP)
* Review of Gradient Descent

7. Deep learning with PyTorch
* Implement MLP with PyTorch
* How to debug PyTorch
* How to monitor the status of the training process
* Other popular types of neural networks

8. Convolutional neural networks
* Theory
* PyTorch implementation
* Data collection and large datasets (HDF5)

9. Image classification with CNNs
* Examples where CNNs surpass humans
* Adversarial examples which trick CNNs but are easy for humans
* Examples of existing CNN models that can be used and modified
* More detail on how to build and train custom models in PyTorch

10. Image segmentation with CNNs
* Examples of existing models that can be used
* How to build and train your own models in PyTorch

11. Advanced network training and validation
* dev-train-test sets
* How to design a custom network and prevent over-fitting
* t-SNE visualization
* Attribution visualization
