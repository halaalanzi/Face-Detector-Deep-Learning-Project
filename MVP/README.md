# Face Detector Using Deep Learning .

The **goal** of this project is to build a deep neural network model that uses image data to extract its features and then recognize it, regardless of lighting, expression, illumination, ageing.

To start with, the images have been preprocessed by resizing the images from 1024x1024 to 256x256 and converting the into arrays. Then, the baseline model has been chosen to be simple neural network with one hidden layer and the accuracy was 0.416 for the training and 0.457 for the validation. Which means accuracy is too low and there is an overfit on the model and to overcome the problem more hidden layers has been added to increase the accuracy and the number of epochs has been decreased to reduce the overfit.

![Bas](https://user-images.githubusercontent.com/93076337/150641380-ec7012d6-a4b3-47de-ad2e-ac6396b17369.png)

The above figure shows the accuracy for both training and validation for each epoch. The blue line represents the training accuracy and the orange line represents the validation accuracy. From the figure it is clear that as the number of epochs increase the training accuracy increase and the gap between training and validation accuracy increases as will.

The next steps, more neural network models will be tested such as convolutional neural network (CNN), convolutional neural network with a Transfer Learning Models will be examined as will.
