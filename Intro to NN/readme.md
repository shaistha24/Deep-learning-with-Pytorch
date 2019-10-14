# Introduction to Neural Networks (NN)

Projects and course work related to Neural Network(NN) introductory level are included here.

**Attention Basics**

Look at how attention is implemented focusing on implementing attention in isolation from a larger model. That's because when implementing attention in a real-world model, a lot of the focus goes into piping the data and juggling the various vectors rather than the concepts of attention themselves.
We will implement attention scoring as well as calculating an attention context vector.

**Batch Normalization**

Batch normalization was introduced in Sergey Ioffe's and Christian Szegedy's 2015 paper Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift. The idea is that, instead of just normalizing the inputs to the network, we normalize the inputs to layers within the network. 
It's called batch normalization because during training, we normalize each layer's inputs by using the mean and variance of the values in the current batch.

**Gradient Descent**

Implementing the basic functions of the Gradient Descent algorithm to find the boundary in a small dataset.

**Predicting Student Admissions with Neural Networks**

Predict student admissions to graduate school at UCLA based on three pieces of data:

GRE Scores (Test)

GPA Scores (Grades)

Class rank (1-4)

The dataset originally came from here: http://www.ats.ucla.edu/


**Sentiment Classification & How To "Frame Problems" for a Neural Network**

1: Quick Theory Validation

2: Creating the Input/Output Data

 3: Building our Neural Network
 
 4: Making Learning Faster by Reducing Noise
 
 5: Making our Network Train and Run Faster
 
  6: Reducing Noise by Strategically Reducing the Vocabulary

