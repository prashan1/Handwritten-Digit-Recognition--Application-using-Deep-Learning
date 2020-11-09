# Handwritten-Character-Recognition-using-CNN
This program allows the user to draw a number on the screen and have the program take a guess of which digit it is. This uses a basic neural network model.
## Abstract
An attempt is made to recognize handwritten characters for English alphabets using multilayer Feed Forward neural network. EMNIST dataset which consists of English alphabets and numbers are made use of to train the neural network. EMNIST balanced dataset consist of  131,600 images of characters and 47 classes .The feature extraction technique is obtained by normalizing the pixel values. Pixel values will range from 0 to 255 which represents the intensity of each pixel in the image and they are normalized to represent value between 0 and 1. Convolutional neural network is used as a classifier which trains the EMNIST dataset. The work is extended by adding some more dataset to EMNIST dataset of characters from Tamil language and training the model. The prediction for the given input image is obtained from the trained classifier.

## Packages used
- [Tensorflow](https://www.tensorflow.org/)
- [Scikit-learn](http://scikit-learn.org)
- [Tkinter](https://wiki.python.org/moin/TkInter)
- [Numpy](http://www.numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Pillow](https://pillow.readthedocs.io/en/5.1.x/)
- [ipython](https://ipython.org/ipython-doc/2/install/install.html)
## Dataset
[EMNIST](https://www.nist.gov/itl/iad/image-group/emnist-dataset) dataset is downloaded and made use by using [python mnist-parser](https://github.com/sorki/python-mnist). Following python code will load emnist-balanced dataset to a python variable

## Example
# 1
![Output3](https://user-images.githubusercontent.com/57286404/80393965-d49e3500-88ce-11ea-97e6-0ccefc07ded6.jpg)
# 2
![Output2](https://user-images.githubusercontent.com/57286404/80394564-a40acb00-88cf-11ea-8ecc-118c9a50305a.jpg)

  
