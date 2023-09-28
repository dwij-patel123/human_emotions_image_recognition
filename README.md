## Human Emotions Image Recognition

#### Where to get Dataset

- [Click here](https://www.kaggle.com/datasets/muhammadhananasghar/human-emotions-datasethes)

#### About This Project

- This project contains various photos of people with "Angry" , "Sad" and "Happy" emotions. The dataset contains two folder Train and Test folder. We need to train a Deep Learning model to identify the emotions of the Project. The deep Model is follow up of LeNet architecture. To know more about LeNet architecture [Click Here](https://en.wikipedia.org/wiki/LeNet). It uses multiple Convolutional Neural Layers followed by Maxpooling layer and at the end a Flatten layer to conver features into a list. We use "Softmax" activation in the last Node as it is a MultiClass Classification Problem.

#### How to make this model better

- As if you run this model you will see that the model Overfits the data so we need to use the following methods:
  - Use Data Augmentation of the Photos
  - To Reduce more layers on the Model
  - Use more Dropout layers
