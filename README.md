# Face-Expressions-Detection
This project Detects  the expression on your face using Sequential model of CNN which is trained on Facial-Expression-Recognition Dataset

# Dataset Link
https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset

# Description
This project is build using the dataset "Facial-Expression-Recognition".The dataset is loaded into the model and different data visualization and deep learning libraries were imported. The dataset is separated into training and test using ImageDataGenerator  function. Here The training data is shuffled to improve the accuracy. Now the model is made ready using 4 CNN layers and 2 fully connected layers. Each CNN layer consists of a Conv 2d layer, Batch normalization function, ReLU activation, Maxpooling2D layer and Dropout layer .Whereas each fully connected layer consists of Dense layer, Batch Normalization, ReLU activation function and a dropout layer. Finally, the output neurons found to be 7 using the softmax activation. Finally, the sequential model is kept ready.By using the TensorFlow Keras library several modules were imported such as Model Checkpoint, Earlystopping, reduceLROnPlateau.The number of epochs to be runned is fixed to be 48 with a batch size of 128. The sequential model developed is made to run on datasets by using several call-back modules. It is observed that the model stops at the 10 epochs due to early stopping and several other call-back modules such as ReduceLROnPlateau etc. The model is then saved .The accuracy was found to be 0.6561. 
