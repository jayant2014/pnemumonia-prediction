# Pnemumonia prediction using Chest X-Ray

This is a solution to pnemonia prediction problem using the kaggle dataset https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

It is trained using VGG16 and InceptionV3 image classifier of Tensorflow + Keras.
Also I have predicted few examples from value dataset using these classifiers.

After training the models with 5 epochs, the accuracy reaches upto 97% using VGG16, whereas in case of InceptionV3 it is 93%.

## VGG16
loss: 0.0671 - acc: 0.9735 - val_loss: 0.3697 - val_acc: 0.8958

![Alt text](AccVal_acc_VGG16.png?raw=true "Accuracy Plot for VGG16")

![Alt text](LossVal_loss_VGG16.png?raw=true "Loss Plot for VGG16")

## Inception V3
loss: 0.5084 - acc: 0.9323 - val_loss: 3.1300 - val_acc: 0.6907

![Alt text](AccVal_acc_InceptionV3.png?raw=true "Accuracy Plot for Inception V3")

![Alt text](LossVal_loss_InceptionV3.png?raw=true "Loss Plot for Inception V3")

So with given dataset VGG16 perform better than Inception V3.
