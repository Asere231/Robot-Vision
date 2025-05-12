# Robot Vision

This repository contains a series of Python-based Jupyter Notebooks focused on key concepts in Robot Vision and Image Processing.

## 📁 Contents
- **1. Image processing in python**: This colab notes provides an introduction to basic image processing techniques using the OpenCV computer vision library and some standard libraries in Python.

- **3 image filtering**: 
 - Applied various filtering techniques to a personal image hosted online. 
 - Implemented and compared 3×3 and 5×5 box filters and multiple Gaussian filters of different sizes. 
 - Performed edge detection using Sobel and Canny algorithms with varying thresholds. 
 - Concluded with morphological operations and contour detection to automatically estimate and visualize the count of rice grains in an image.

- **5 ImageWarping**: 
 - Explored image transformations and homographies using matrix operations in homogeneous coordinates.
 - Performed rotation and translation on point sets to study transformation composition and matrix inversion.
 - Implemented forward warping of an image using a homography matrix and visualized warping artifacts.
 - Developed a nearest-neighbor interpolation technique to improve warped image quality.
 - Created reusable functions to apply homographies and recover transformation matrices from point correspondences.
 - Bonus work included building a generalized image warping function using forward and inverse mapping with bilinear interpolation.

- **Project 1**: 
 - Developed a Python-based document rectification tool inspired by apps like CamScanner.
 - Implemented manual image warping by allowing users to select document corners, computing the homography matrix, and applying backward warping to correct perspective distortion.
 - Tested the pipeline on high-resolution document images.
 - Also explored automated corner detection techniques for fully automated rectification, and evaluated performance on sample test images.
 - Emphasized robustness, accuracy, and potential improvements for better document localization.

- **project2**: 
 - Built and trained multiple neural networks and convolutional neural networks (CNNs) for image classification tasks using the MNIST and CIFAR-10 datasets in PyTorch.
 - In Part 1, experimented with shallow and deep fully connected networks for digit recognition, modifying hyperparameters, adding activation functions (ReLU), and analyzing training/testing performance metrics.
 - In Part 2, implemented CNN architectures with varying filter depths and layers for classifying colored images in CIFAR-10.
 - Ran multiple experiments with different learning rates and epoch settings, visualized training curves, tested accuracy, and discussed performance trade-offs based on network size and training duration.

## 🛠 Technologies Used
- Python 3.x
- OpenCV
- NumPy
- Jupyter Notebooks

## 📝 Notes
Each notebook is self-contained and includes explanations, code examples, and visual outputs to reinforce robot vision concepts.
# Robot-Vision
