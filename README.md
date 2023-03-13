# Face-Emotion-Recognition-using-DCNN
Face emotion recognition which recognize the emotion of the person (i.e. the person is happy, sad) using DCNN with 6 convolution layers and 2 fully connected layers.


In this model I have used fer2013 dataset The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 3,589 examples.

The number of data in each of the seven classes wasn't particularly close.
![image](https://user-images.githubusercontent.com/67710906/224713357-8819a9ce-2d3d-4441-b5ba-bc020081624c.png)


With this model, we were able to obtain 78% accuracy

![image](https://user-images.githubusercontent.com/67710906/224713591-a4ee2d27-7b8f-4918-aeb0-8ba6505f25f7.png)
