# IMAGE CLASSIFICATION

## MOTIVATION:
* Image recoginiton can be of help in many fields such as object detection and autonomous driving.

## TASK:
* In this project we classify images into 10 classes.

## DATASET:
* The data used here is taken from Tensorflow datasets. To access the dataset click [here.](https://www.tensorflow.org/datasets/catalog/cifar10)
* Here is a look at the dataset.
* ![dataset](https://i.ibb.co/s2xBsBq/image-classes.jpg)

## TRAIN and TEST DATA:

|DATA               | SAMPLE SIZE  |
|----               | -----        |
|Train_data         | 50,000       |
|Test_data          | 10,000       |

## IMAGE PIXELS:
* The image in this dataset are grayscale images. The dimension of each image is (28,28,3).
* The height and width of the image is equal to 28.
* Number of channels in the image are three Red, Blue and Green.

## NEURAL_NETWORK ARCHITECTURE:
* In this project we made use of the convolutional neural network.
* Then we flatten the output of the convolutional network and add fully conncted layers to it.
* ![LENET-5](https://i.ibb.co/7CKTS2w/model.jpg)

## EPOCHS VS ACCURACY
* Here is a look at the epoch vs accuracy for training and validation dataset.
* ![graph](https://i.ibb.co/QjwP7Lh/graph.jpg)

## CLASSIFICATION REPORT:
* ![classification_report](https://i.ibb.co/ckpHSqH/classification-report.jpg)
