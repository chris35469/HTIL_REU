# Machine Learning


## Videos

### Linear Algebra

[![Linear Algebra](http://img.youtube.com/vi/kjBOesZCoqc/0.jpg)](http://www.youtube.com/watch?v=kjBOesZCoqc)


### Activation Functions

[![Activation Functions](http://img.youtube.com/vi/-7scQpJT7uo/0.jpg)](http://www.youtube.com/watch?v=-7scQpJT7uo)


### What is a Neural Network

[![Linear Algebra](http://img.youtube.com/vi/aircAruvnKk/0.jpg)](http://www.youtube.com/watch?v=aircAruvnKk)

### Gradient descent, how neural networks learn

[![Linear Algebra](http://img.youtube.com/vi/IHZwWFHWa-w/0.jpg)](http://www.youtube.com/watch?v=IHZwWFHWa-w)

### Backpropagation

[![What is backpropagation really doing?](http://img.youtube.com/vi/Ilg3gGewQ5U/0.jpg)](http://www.youtube.com/watch?v=Ilg3gGewQ5U)

### Backpropagation Calculus
[![Backpropagation Calculus](http://img.youtube.com/vi/tIeHLnjs5U8/0.jpg)](http://www.youtube.com/watch?v=tIeHLnjs5U8)


### Long Short-Term Memory
[![Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM)](http://img.youtube.com/vi/WCUNPb-5EYI/0.jpg)](http://www.youtube.com/watch?v=WCUNPb-5EYI)


## Links

### Blogs / Articles
[The Unreasonable Effectiveness of Recurrent Neural Networks Blog Post](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

[Data Science and Robots Blog](https://brohrer.github.io/blog.html)

[Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)

[EEG event classification with convolutional neural networks - A First Pass/Brief Overview](https://www.reddit.com/r/MachineLearning/comments/8mc5jx/p_eeg_event_classification_with_convolutional/)

[Reddit Machine learning](https://www.reddit.com/r/MachineLearning/)

[Closing the Simulation-to-Reality Gap for Deep Robotic Learning](https://ai.googleblog.com/2017/10/closing-simulation-to-reality-gap-for.html)

[pybullet by Alexander Fabisch](http://alexanderfabisch.github.io/pybullet.html)

[Pytransform - lightweight tool to translate between conventions, debug, and visualize](http://alexanderfabisch.github.io/pytransform.html) 

[Alexander Fabisch - Robotics Python](http://alexanderfabisch.github.io/)

### Code

[Torch-rnn Char-rnn update](https://github.com/jcjohnson/torch-rnn)

[Xgboost](https://github.com/dmlc/xgboost)

[Xgboost Node](https://www.npmjs.com/package/xgboost)

### Frameworks & Websites

[TensorFlow](https://js.tensorflow.org/)

[Keras](https://keras.io/)

[Try TensorFlow](https://codepen.io/pen?&editors=1011)

[Colab](https://colab.research.google.com/notebooks/welcome.ipynb#recent=true)

[Kaggle](https://www.kaggle.com/)

[Moniel - Interactive Notation for Computational Graphs ](https://github.com/mlajtos/moniel)

[OpenAI](https://openai.com/)

[OpenAI Github](https://github.com/openai)

[DeepMind - Lab 3D platform for agent-based AI research](https://github.com/deepmind/lab)

[DeepMind - Sonnet](https://github.com/deepmind/sonnet)

[Install Anaconda](https://docs.anaconda.com/anaconda/install/linux)

### Companies

[Baidu](http://research.baidu.com/)

[DeepMind](https://deepmind.com/)

### Books

[Deep learning with python book] (http://proquestcombo.safaribooksonline.com.libdata.lib.ua.edu/book/programming/python/9781617294433)

[Deep learning with python code](https://github.com/fchollet/deep-learning-with-python-notebooks)

[Neural Networks and Deep Learning by Michael Nielsen](http://neuralnetworksanddeeplearning.com/index.html)

[Programming Robots with ROS](http://proquestcombo.safaribooksonline.com.libdata.lib.ua.edu/book/hardware/9781449325480)

[ROS Programming: Building Powerful Robots](http://proquestcombo.safaribooksonline.com.libdata.lib.ua.edu/book/programming/9781788627436)

[ROS Robotics By Example](http://proquestcombo.safaribooksonline.com.libdata.lib.ua.edu/book/hardware/9781782175193)

### Lectures

[Recurrent Neural Network Lecture](https://www.youtube.com/watch?v=iX5V1WpxxkY)

### People

[Andrej Karpathy](https://twitter.com/karpathy)

[Andrew Ng](https://twitter.com/AndrewYNg)

[Geoffrey Hinton](https://scholar.google.co.uk/citations?user=JicYPdAAAAAJ&hl=en)



# Notes

- **Convolutional Neural Network (CNN)** good for **image recognition**
- **Recurrent Neural Networks** and **Long short-term memory** good for **speech recognition**
- Transforming a set of real numbers to normalized values **Logistic functions**, **Logistic Curve** - [Signmoid Function](https://www.quora.com/What-is-the-sigmoid-function-and-what-is-its-use-in-machine-learnings-neural-networks-How-about-the-sigmoid-derivative-function)
- **Weight engineering**? applying weights to areas/components you care about.
- **Cost function** provides feedback to the network
- Learning is minimizing a cost function
- Categorical data is handled using [One hot encoding procedures](https://www.kaggle.com/dansbecker/using-categorical-data-with-one-hot-encoding)

## Activation Function & General Notation

##### Notation for weights and neuron activations 
(Note: Sigmoid approach replaced by RELU activation function)

![Notation for weights and neuron activations](img/nn_notation.png "Notation for weights and neuron activations")
![Notation for weights and neuron activations](img/nn_notation2.png "Notation for weights and neuron activations")

## BackProp

##### Chain Rule (Calculus) and relevance to cost function in Neural networks (Backprop)(One neuron)
![alt text](img/nn_notation3.png "Notation for chainrule backprop (one neuron)")
![alt text](img/nn_notation3b.png "Notation for chainrule backprop (one neuron) derivatives")
 
##### Chain Rule (Calculus) and relevance to cost function in Neural networks (Backprop)(multi neuron)

![alt text](img/nn_notation4a.png "Notation for chainrule backprop (multi neuron)")

![alt text](img/nn_notation4.png "Notation for chainrule backprop (multi neuron)")


