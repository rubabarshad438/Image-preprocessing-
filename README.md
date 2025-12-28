 CIFAR-10 Image Transformations & Augmentation using PyTorch

This repository demonstrates image preprocessing, data augmentation, visualization, and custom filtering using PyTorch and Torchvision on the CIFAR-10 dataset.  
It is designed for Artificial Intelligence students and beginners to understand how image data is prepared before training deep learning models.

 Project Overview

In deep learning, raw images cannot be used directly. They must be processed, transformed, normalized, and augmented.  
This project applies multiple transformations step-by-step and visually analyzes their effect on image tensors.

 Features

-  Automatic loading of CIFAR-10 dataset
-  Image resizing to 64×64
-  Grayscale conversion (3-channel compatible)
-  Random image rotation (±45°)
-  Horizontal image flipping
-  Pixel normalization to range [-1, 1]
-  Custom sharpening filter using convolution
-  Image visualization using Matplotlib
-  Tensor analysis (shape, min, max values)
-  Final batch preparation for CNN input

Dataset Details

- Dataset: CIFAR-10  
- Images: 60,000 RGB images  
- Image Size: 32×32  
- Classes: 10 (airplane, automobile, bird, cat, etc.)  
- Source: Automatically downloaded using `torchvision.datasets`

 Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib


```python
T.Resize((64, 64))
# Image-preprocessing-
