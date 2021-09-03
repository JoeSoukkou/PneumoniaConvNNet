# PneumoniaConvNNet
A Convolutional Neural Network for Classifying Pediatric Chest X-rays Into Pneumonia vs Normal Implemented in PyTorch.
## Dataset 
The Dataset used to train and test this model was obtained from https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia, with only slight modifications being done on it (i.e. equalizing the pneumonia vs normal chest xrays for training to avoid problems with learning)
## Accuracy
the Final Obtained Accuracy of this ConvNet was 94.02% for a training set of only 1341 Images for each Class.
## Learning Rate
the used learning rate was 0.0008.
## Epochs
Model was obtained after 8 epochs of training 
## Loss
using the built-in nn.MSELoss, a value of 0.0076 was obained


#Please feel free to tweak this project's params and try to get a better accuracy without over-fitting
