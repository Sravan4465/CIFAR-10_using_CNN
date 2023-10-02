# CIFAR-10_using_CNN
Image Classification using CNN

Using Convolutional Neural Network (CNN) based deep learning method implementing two models for performing classification on CIFAR-10 dataset.

CIFAR-10 dataset consists of 60000 images of size 32x32x3.

I have implemented two models one without data augmentation and other with data augmentation.
Model trained without data augmentation reached its limit in just 20 epochs from there it is overfitting the data.
But for the model trained using data augmentation learns for more than 120 epochs and also shows good accuracy and loss compared to previous one.

|           Model           |   val_Loss  |    val_Accuracy   |
|---------------------------|-------------|-------------------|
| Without Data Augmentation |    0.976    |      66.52 %      |
|  With Data Augmentation   |    0.7310   |      75.26 %      |



