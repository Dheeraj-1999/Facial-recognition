# Facial-recognition

## GOALS:

* DESIGN A DEEP CONVOLUTIONAL NEURAL NETWORK USING KERAS( TENSORFLOW HIGH LEVEL API).
* USE OPENCV FOR DETECTING THE FACE OF A PERSON USING ITS FACE DETECTION CLASSIFIER ALSO DRAWS BOUNDING BOXES AROUND THEM.
* DEPLOY THE TRAINED MODEL TO A WEB INTERFACE USING FLASK.
* CLASSIFY THE OWN COMPUTER WEBCAM.

## explore the dataset:

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

The training set consists of 28,709 examples.

[Dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)

### hierchy:
* Dataset
  * test(80%)
   * Angry 
   * Disgust 
   * Fear 
   * Happy 
   * Sad 
   * Surprise
   *Neutral
  * train(20%)
   * Angry 
   * Disgust 
   * Fear 
   * Happy 
   * Sad 
   * Surprise
   *Neutral

* data is given in csv format.
* data is converted to images then saved it to train and test folder
* DATA SIZE OF EACH CATEGORY.
3995 angry images
436 disgust images
4097 fear images
7214 happy images
4965 neutral images
4830 sad images
3171 surprise images
   
