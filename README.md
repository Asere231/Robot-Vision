# Robot Vision

This repository contains a series of Python-based Jupyter Notebooks that explore fundamental and advanced topics in Robot Vision and Image Processing.

## 📁 Contents

### **1. Image Processing in Python**
Introduces basic image processing techniques using OpenCV and standard Python libraries in a Colab environment.

### **3_image_filtering.ipynb**
- Applied 3×3 and 5×5 box filters to analyze the effects of kernel size.
- Compared multiple Gaussian filters with varying kernel sizes.
- Performed edge detection using Sobel and Canny algorithms.
- Used morphological operations and contour detection to count rice grains in an image.

### **5_ImageWarping.ipynb**
- Explored image transformation using homogeneous coordinate matrices.
- Applied sequential rotation and translation to point sets.
- Performed forward warping using a homography matrix.
- Implemented nearest-neighbor interpolation to refine warped output.
- Developed reusable functions to compute and apply homographies.
- Bonus: Built a general image warping function with bilinear interpolation and both forward/inverse mapping.

### **Project_1.ipynb**
- Built a Python tool for document rectification inspired by apps like CamScanner.
- Enabled manual corner selection and computed homography-based transformation.
- Applied backward warping to correct perspective distortion.
- Explored automated document corner detection methods and evaluated performance.

### **project2.ipynb**
- Trained various neural networks for image classification using PyTorch.
- **Part 1:** Designed and tested simple to deep fully connected networks for MNIST digit recognition.
- **Part 2:** Built CNNs for CIFAR-10 classification with experiments on filter depth, learning rates, and training durations.
- Visualized training/test loss curves and accuracy metrics, and discussed model behavior and efficiency.

## 🛠 Technologies Used
- Python 3.x  
- OpenCV  
- NumPy  
- PyTorch  
- Jupyter Notebooks  

## 📝 Notes
Each notebook is self-contained and includes comments, code examples, training visualizations, and written analysis to support learning in robot vision and deep learning.

