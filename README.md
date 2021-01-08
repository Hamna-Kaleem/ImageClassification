# ImageClassification
This repository contains **Image Classification** code with **Transfer Learning** to build deep learning models using keras. Three state of the art CNN architectures i.e. **VGG16, Resnet50, InceptionV3** is selected to perform image classification on natural images dataset. **Data augmentation** techniques are also used to compare the results of selected models. Accuracy of the models are compared among the models on the basis of best test accuracy of the model on given dataset and on augmented dataset.

**Dataset** contains 25k images with 150 x 150 x 3 size and have 6 classes i.e. buildings, forests, glaciers, mountains, seas, streets and each class has a number assigned to it i.e. 0,1,2,3,4,5 respectively.

**Transfer Learning** : VGG16, InceptionV3, Resnet50 is used. Softmax and dense layer is added at the end of the model to predict six classes of given data.

**Data Augmentation** : Horizontal, Vertical flip set to True, scaling is set to 01% and rotation of 90 degree is applied.

**Best Results** : VGG16 has the best test accuracy results with 86.46%

![Screenshot](https://github.com/Hamna-Kaleem/ImageClassification/blob/main/vgg16.jpeg?raw=true)

**Strange Shift in Accuracy** : Resnet50 show high testing accuracy with augmented data i.e. approximately 63.86% but without augmentation model was inable to perform well in testing phase and had testing accuracy just 14.13% with the highest test loss of 18.53

![Image](https://github.com/Hamna-Kaleem/ImageClassification/blob/main/resnet50.png?raw=true)
