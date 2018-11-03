# Deep-Learning

## What is Machine Learning?
From the beginning when we learn math we are learning functions. For a straight line, it can be f(x) = x +3. When the input x = 3, it is quite easy to get f(3) = 6.

If the input is an audio, you need to simulate something similar to a function. The function would output the content of the input audio.

**f(![image](https://github.com/mattliu777/Deep-Learning/blob/master/image/audioicon_e4_rel.jpg)) = "Hello World"**

If the input is a picture, you want to simulate a complex function so that its output is what this picture is.

**f(![image](https://github.com/mattliu777/Deep-Learning/blob/master/image/p0517py6.jpg)) = "Cat"**

If the input is a Go board, you want to simulate a complex function and let it tell you where to go next.

**f(![image](https://github.com/mattliu777/Deep-Learning/blob/master/image/main-qimg-db601a17da862a35f8ad006aa70e96f1-c.jpg)) = "1-2"**

Yes, you can think that machine learning is looking for this complicated "function" because it is complex, it is not certain, it is nonlinear, so you need to design some algorithms to let the machine learn what exactly is this complicated "function". That's what machine learning is. People will make some decisions, some judgments, you hope, using some existing data, training the machine, so that the machine can also learn how to make decisions, or even do better.

## What is Deep Learning?
Deep learning is a subclass of machine learning. In other words, it is actually a way to implement machine learning. With the rapid development of computer hardware and software, people realize that the neural network can be used to simulate the human brain, and the word depth means nerve. The network has many layers. Looking back, how do you think about your brain? How does your biology teacher tell you how the signal is transmitted in the brain.

At present, deep learning mainly has:

**Convolutional Neural Network**

**Recurrent Neural Network**

**Generative Adversarial Networks**

**Deep Reinforcement Learning**

## How to Start?
**What to learn?** The first subject to learn or to start should be CNN.

**How?** 
  **Books**
    [Deep Learning](http://www.deeplearningbook.org/)
  **Course**
    [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)
    [Machine Learning and having it deep and structured (2017,Spring)](http://speech.ee.ntu.edu.tw/~tlkagk/courses_MLDS17.html)
    [Deep Learning Andrew Ng](https://www.coursera.org/specializations/deep-learning)

## The stuff you should cover

  Understand what is Image Classification
  
  Make prediction with some simple linear models(SVM,KNN)
  
  Learn about Optimization, LossFunction and Gradient descent
  
  Learn about Backpropagation
  
  Learn about Neural Network
  
    Learn about Normalization, Pooling, Convolution
  
    Get hands on Tensorflow，Keras，Pytorch，Caffe
    
    read other project's code
    
    Learn about cifar10 and ImageNet
  
  Start your first CNN model: **[LeNet-5 - Yann LeCun](http://yann.lecun.com/exdb/lenet/)**
  
  Then **[AlexNet](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks)**
  
  Then **[ZF Net](https://arxiv.org/abs/1311.2901)**
  
  Also **[Network in Network](https://arxiv.org/abs/1312.4400)**
  
  And start to learn some CNN training trick:
      
      Data Augmentation
      
      Xavier/He Weight initial
      
      Batch Normalization
      
      L2/L1/Maxnorm/Dropout
      
  Learn the famous **[Vgg Network](https://arxiv.org/abs/1409.1556)**
  
  Also the google family **GoogleNet**
      [Going Deeper with Convolutions](https://arxiv.org/abs/1409.4842)
      [Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/abs/1502.03167)
      [ Rethinking the Inception Architecture for Computer Vision](https://arxiv.org/abs/1512.00567)
      [ Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning](https://arxiv.org/abs/1602.07261)
      
  Learn **Fine-tune**, start to improve code
  
  Don't forget the [Residual Network](https://arxiv.org/abs/1512.03385)
  
  [Aggregated Residual Transformations for Deep Neural Networks](https://arxiv.org/abs/1611.05431)
  
  
      
