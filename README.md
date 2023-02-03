# Face-emotion-detection-project

In a face emotion detection project, the goal is to build a system that can automatically identify and classify the emotion being expressed by a person in a given image or video frame. This can be used in a variety of applications, such as detecting emotions in customer service interactions, detecting emotions in social media posts, or detecting emotions in marketing research.

dataset-- https://www.kaggle.com/datasets/msambare/fer2013

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.

The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 3,589 examples

#### Validation result

![image](https://user-images.githubusercontent.com/94167271/211168903-0ff9c624-8825-4f06-9aa4-ac521a064ea9.png)
Best Validation Accuracy Score 0.66520

use TestEmotionDetector.py to test model on video or webcam

#### webcam result on video

![Screenshot (emotion](https://user-images.githubusercontent.com/94167271/211168986-30826bd7-6dfd-47d1-9bd8-42c03fdf3629.png)



