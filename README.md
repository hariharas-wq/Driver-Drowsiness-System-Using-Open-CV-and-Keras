# Driver-Drowsiness-System-Using-Open-CV-and-Keras
The convolutional neural network is a special type of deep neural network that works very
well for the purposes of image classification. CNN basically contains an input layer, an
output layer and a hidden layer that can contain multiple number of layers. The convolutional
work is done on these layers using a filter that makes 2D matrix multiplications in the layer
and filter.
CNN model architecture consists of the following layers:

• Convolutional layer; 32 nodes, kernel size 3
• Convolutional layer; 32 nodes, kernel size 3
• Convolutional layer; 64 nodes, kernel size 3
• Fully connected layer; 128 points

Convolutional Neural Network: In deep learning, CNN is widely used to perform image
classification, object detection, image recognition, face recognition and several other
functions related to image processing. CNN usually contains input layer, output layer and
hidden layers. The number of hidden layers varies depending on the complexity of the model.
Typically, in an in-depth study of CNN models, each frame is processed through a series of
flexible layers with filters and processed using activation functions to make classification
possible values; in actual practice, these values are between 0 and 1. Over the past few years,
several major advances in feature learning have been made with the introduction of models
such as Deep Boltzmann Machines (DBM), Deep Belief.
Networks (DBN), Convolutional Neural Networks (CNN), Limited Boltzmann Machine
(RBM), Standard Neural Networks (RNN), Au-toencoders and many more. Most of these
networks use a lot of hidden layers for maximum layout. In the proposed model, the same
type of convolutional neural network is used.
Several tests were performed using various hidden layers until the correct number of hidden
layers was found to provide high accuracy. First, two hidden layers were selected that
provided about 50% accuracy, which is not at all satisfactory. Then, to improve accuracy,
another hidden layer was added that almost doubled the accuracy. Changing the number of
variable layers from 2 to 3 has greatly improved the accuracy (from about 50% to about
98%). However, changing the number of dense layers did not have a significant impact on
accuracy. Similarly, changing the number of nodes in each layer also did not change the
accuracy of any significant value. Finally, a model with 3 layers of flexibility (first 3x3x32,
second 3x3x32 and third 3x3x64) and 2 compact layers (128 and 2) reached almost 100%
accuracy after 10 seasons therefore two drop-off layers have been added to prevent overlap.
## Working Architecture :
Step 1 – Take an image as input from a camera.
Step 2 – Detect the face in the image that has been in the frame and create a Region of
Interest (ROI).
Step 3 – Detect the eyes from the Region of Interest and feed it to the classifier.
Step 4 – Classifiers will be used to categorize whether eyes are open or closed.
Step 5– Calculate the score upto which a driver’s eyes are closed to check whether the person
is drowsy.
