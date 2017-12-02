This repo contains code for images of traffic sign classification from *German Traffic Sign Database* [GTSRB](http://benchmark.ini.rub.de/?section=gtsrb&subsection=news). 

The train dataset consists of 39209 images with 32x32 px resolution, test dataset - 12630. The datasets were provided by *Udacity*.

## Notebooks:

Finally, **95.0%** accuracy on the test dataset achieved with one Convolutional neural network, based on GoogLeNet inception modules. The code uses TensorFlow only.

`Traffic_Sign_Classifier-2Net.ipynb` Experiments with two Convolutional neural network, also based on inception modules. Basic idea: train two CNN: one - for traffic sign classification in general, and second - for numbers on speed limit sign classification. This implementation uses Keras with TensorFlow as backend.
