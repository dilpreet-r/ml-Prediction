# ml-Prediction

This application can  predict the image provided to it using machine learning as what it is.

Here, I have used ImageAI library which can be used to build applications and systems with self-contained Computer Vision capabilities.

This application uses ResNet50 for Image Prediction by Microsoft Research (Size = 98 mb, fast prediction time and high accuracy)

First of all, clone this repository into your system.

To use ImageAI in your application developments, you must have installed the following dependencies before you install ImageAI :

Python 3.5.1 (and later versions)
Tensorflow 1.4.0 (and later versions) (Tensorflow 2.0 coming soon)
OpenCV
Keras 2.x

Use: pip install -U tensorflow keras opencv-python

After that download ResNet50 from https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_weights_tf_dim_ordering_tf_kernels.h5 and save it in the same folder having other files like mlapp.py, etc.

Then, all you need to do is run command: ( python mlapp.py img.jpg ) where img.jpg is the image you want to predict and it can be of any extension.

Argument following python mlapp.py is the image you want to predict.

Important: Image to be predicted must be in same folder as of mlapp.py
