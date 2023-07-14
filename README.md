# SRCNN

SRCNN is a method for single image super-resolution.It learns an end-to-end mapping between the low/high-resolution images.The mapping is represented as a deep convolutional neural network (CNN) that takes the low-resolution image as the input and outputs the high-resolution one.

# Architecture
![tempsnip](https://github.com/TONY19950506/SRCNN/assets/110157487/ea51051e-3819-455f-b9b6-929fcf43db07)

The network structure of SRCNN is simple, using only three convolutional layers
1. Patch extraction and representation
2. Non-linear mapping
3. Reconstruction
