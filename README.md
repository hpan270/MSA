# MSA
Microsoft Student Accelerate Program (NZMSA)

I built a CNN model with 4 stacked Conv2D layer and trained it one Google Colab with one free GPU.
keras_cifar10.ipynb contains the code, and results in CNN_Results folder


1. CNN structure is the code from Keras Cifar10 CNN example, refer to
https://github.com/keras-team/keras/blob/master/examples/cifar10_cnn.py


2. I made the code to 
- use keras callbacks,  save the mode in json, weights in hdf5 and training acc/loss in csv
- plot the training/validation acc/loss via epochs
- the classification report: precision, recall, f1, support score
- plot the confusion matrix


3. The result:
- 4 Conv2D layers, stacked, 100 epochs: score 78
- 4 Conv2D layers, stacked, data augment, 32 epochs: score 84
