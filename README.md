# SRCNN

SRCNN is a method for single image super-resolution.It learns an end-to-end mapping between the low/high-resolution images.The mapping is represented as a deep convolutional neural network (CNN) that takes the low-resolution image as the input and outputs the high-resolution one.

# Architecture
![tempsnip](https://github.com/TONY19950506/SRCNN/assets/110157487/ea51051e-3819-455f-b9b6-929fcf43db07)

The network structure of SRCNN is simple, using only three convolutional layers
1. Patch extraction and representation

     ![tempsnip](https://github.com/TONY19950506/SRCNN/assets/110157487/ee7489a8-2278-42c9-8dc7-6dedf70b0777)

3. Non-linear mapping

     ![tempsnip](https://github.com/TONY19950506/SRCNN/assets/110157487/e78c4475-8534-4828-8968-43783d9a71d5)

3. Reconstruction

     ![tempsnip](https://github.com/TONY19950506/SRCNN/assets/110157487/90b2790e-55f7-4f26-806b-c4da9c00aa27)

# Loss function 
Use Mean-square error(MSE) to be it's loss function.Among them,minimizing MSE is maximizing PSNR.
     ![tempsnip](https://github.com/TONY19950506/SRCNN/assets/110157487/9608040a-2163-4bf9-beac-ca17bbeb8915)
     ![tempsnip](https://github.com/TONY19950506/SRCNN/assets/110157487/20fda5ba-331c-458c-9ece-cbba9335c7c0)

