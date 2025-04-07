# NeuralNets from Scratch 
This repository contains foundational concepts that are coded in **Python** programming language to understand the working of Neural Networks and how the hyperparameters contribute to the accuracy and loss of the whole Network.

# Libraries

1. Numpy - used majorly to code the neural networks from scratch
2. Matplotlib - for visualizations
3. PyTorch - used in projects
4. NNFS - this is used as a dataset in coding the neurons from scratch

The whole repository is structured in two parts: 
- **Neural Networks built from Scratch** 
- **Projects** - using PyTorch

# Neural Networks built from Scratch

This module contains 5 Jupyter notebooks containing codes from building a single neuron to a full-fledged Neural Network. 
In these notebooks, initially, I coded a single neuron without any activation functions.
Then, eventually, I started to  build the Layer class with a forward pass method.
This led me to build ReLU, Softmax, and Sigmoid activation functions with forward pass methods.

After the key components of the network, I moved towards calculating the loss.
That eventually led to work on the concept of **BackPropagation**, the key to modern day Neural Networks. 
After successfully coding the backward pass for each component, I moved to another major part of the architecture, i.e, **Optimizers**.
This optimizes the loss calculated from BackPropagation to generate better predictions.

The Optimizer module discussed Stochastic Gradient Descent with a fixed learning rate, followed by learning rate decay.
The concept of **Momentum** was later introduced.

There were 3 Optimizers in this module :

- **Adagrad** Optimizer
- **RMSProp** Optimizer
- **Adam** Optimizer

Finally, **Overfitting**, ML Engineer's nightmare ;) was discussed.
How to have a good generalized model was discussed.....
Few methods discussed : 

- **K-Fold Validation**
- **L1/L2 Regularization**
- **Dropout**


# Projects
- **MNIST Fashion Data Classifier** :
  This project is a starter project in PyTorch to understand the whole process, starting from data preprocessing to model prediction. Here, the training data is 60000, and the testing data is 10000. The training data is further divided to validation data. Built a basic Neural Network. You can check the notebook ...

- **Heart Disease Classifier** :
  This is a project that classifies heart disease based on 14 parameters. In this dataset, there were a few inconsistencies that were cleaned, and some data was one-hot encoded for input preparation for the model. The model arch wasn't very complex. 


Here we come to the end of the whole repo....
Connect me over [LinkedIn](www.linkedin.com/in/snehal-python) or [X](https://x.com/naive_ai_)

Study Material & Tutorials [Vizuara AI Labs](https://youtube.com/playlist?list=PLPTV0NXA_ZSj6tNyn_UadmUeU3Q3oR-hu&si=fOFUtpF7WlsM0PG3)
