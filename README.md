# Convolutional-Neural-Network
In machine learning, a convolutional neural network (CNN, or ConvNet) is a class of deep, feed-forward artificial neural networks, most commonly applied to analyzing visual imagery.
CNNs use a variation of multilayer perceptrons designed to require minimal preprocessing. They are also known as shift invariant or space invariant artificial neural networks (SIANN), based on their shared-weights architecture and translation invariance characteristics.

Convolutional networks were inspired by biological processes, in that the connectivity pattern between neurons resembles the organization of the animal visual cortex. Individual cortical neurons respond to stimuli only in a restricted region of the visual field known as the receptive field. The receptive fields of different neurons partially overlap such that they cover the entire visual field.

CNNs use relatively little pre-processing compared to other image classification algorithms. This means that the network learns the filters that in traditional algorithms were hand-engineered. This independence from prior knowledge and human effort in feature design is a major advantage.


IN This project we used MNIST dataset as it is easily available and there is already preprocessing done on the dataset
and its size is good enough to train our CNN model
--> in this model we use 2 convolutional layers with RElu activation function having stride of 1, and use 
   max_pooling to reduce the dimensions of the convolution layer, after that we flatten the last convoluted + max-pooled layer and convert it into 1 dimensional array then use these flatten layer for classification purpose.
