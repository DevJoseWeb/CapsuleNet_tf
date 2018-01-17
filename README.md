Capsule Networks
==========================

Implemented using TensorFlow<br>
Based on the paper "Dynamic Routing Between Capsules"

# Requirements
* python3
* TensorFlow
* NumPy
* Matplotlib

# Dataset
* MNIST datasets
You can download at [download link](http://yann.lecun.com/exdb/mnist/)
and locate them in the './MNIST_data' directory.

# How to run Training & Testing
Locate the MNIST datasets in the './MNIST_data' directory and just run capsNet.ipynb

# Results
## Accuracy
* The best error


## Sample MNIST Test Reconstruction
<img src="./images/Fig2_Reconstruction.png">
* The images on the first row are the input images, and that on the second row are the reconstructions.
* We can see that the reconstructions preserves many of the details of the input while smoothing the noise.

## What the individual dimensions of a capsule represent
* We can see what the individual dimensions represent by feeding a perturbed version of the activity vector to the decoder network and see how the perturbation affects the reconstruction.
* By the experiment, the representations of each dimension are as follows.
