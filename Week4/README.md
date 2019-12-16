
## 30th March 2019

Mini_Hackathon: Authorship verification for short messages using stylometry

---

## 31st March 2019

Lectures:
1. Lecture 5: PCA and EigenFaces, Multi-Layer Perceptron
2. Lecture 6: Features for Perception-1, Features for Perception-2

Other Topics:
    1. **Principal Component Analysis (PCA)**
        * Three Generations of Features or Representations
        * Feature Selection and Extraction
        * Dimensionality and Representation
        * Find the prominent direction (a vector)
        * Compute Eigen vectors and Eigen values
        * PCA and Covariance Matrix
        * Covariance
        * PCA based Feature Extraction
        * Principal Component Analysis
        * How many Eigen vectors to pick?
    2. **3Blue1Brown - Linear combinations** - https://www.youtube.com/watch?v=k7RM-ot2NWY
    3. **Eigenfaces**
        * PCA into action
    4. **Features for Images**
        * First Generation - Handcrafted: A Naive Attempt
        * Possible Features: Handcrafting
        * Possible Features: Raw Data Itself
        * Visual BoW: Basic Idea
        * Visual Bag of Words
        * Second Generation - Statistical
        * Visualizing EigenVectors as Images
        * Representing with EigenFaces
        * PCA/EigenFace Algorithm: Detail
        * Third Generation - Learn
        * Deep features - To be determined by experiments


---


## 13th April 2019

Experiments:
1. Expt 8: MNIST-MLP Expt
2. Expt 9: Celebrity Faces - PCA
3. Expt 10: CIFAR-100
4. Expt 11: Eigenfaces for classification
5. Expt 12: Speech-""Yes""/""No"" Classifier"


---


## 14th April 2019

Lectures:
1. Lecture 7: Visualization
2. Lecture 8: Cloud APIs

Experiments:
1. Expt 13: Visualization - TSNE
2. Expt 14: Visualization - ISOMAP
3. Expt 15: Alexa API Experiments

--- 













## M2: Closer Look at AI/ML Algorithms
    * Linear Algorithms, Optimization and Training
    * Non-Linear Solutions and MLP
    * Gradient Descent and Backpropagation
    * Decision Trees, Random Forest, and Ensembles
    * Principles and Practice of ML
    * Support Vector Mahines and Kernels


---


## 20th April 2019

**Hackathon**: Voice commands based food ordering system

---


## 21th April 2019

Lectures:
1. Lecture 9: Convolutional Layer
2. Lecture 10: Back Propagation
3. Lecture 11: ML Pipeline
4. Lecture 12: Overfitting and Generalization

**Convolutional Layer**

    * Convolutional Neural Networks aka CNN
    * Convolution layer in 2D
    * Convolution in 2-D

**Back Propagation**

    * Back Propagation
    * Neuron, Perception and MLP
    * Loss or Objective
    * Error Back Propagation
    * Neural Network Training
    * Chain Rule
    * Forward-Propagation


**ML Pipeline**

    * Complexity Vs. Goodness of Fit
    * Why do we evaluate a model's performance?
    * Reporting results
    * How to measure performance?
    * How to perform the split?
    * Common Splitting Strategies
    * Imbalanced Class Sizes
    * Evaluating a model with imbalanced data

    Cross Validation K fold leave one out
        * k-fold and Leave One Out
        * k-fold cross-validation


**Overfitting , Regularization and Generalization**

    * How to prevent/reduce overfitting?
        1. Early Stopping
        2. Effect of Regularization
    * Curve fitting with different regularizations
    * L1 Regularisation

    * What is the best model?
    * What is the best classifier?
    * Memorization and generalization
    * Generalization
    * Occam's Razor


---







## 27th April 2019

Experiments:
1. Expt 16: Leave one out Validation
2. Expt 17: K-fold Validation Expt
3. Expt 18: Polynomial Curve Fitting


---

## 28th April 2019

Experiments:
1. Expt 19: K-Means
2. Expt 20: Hierarchical Clustering
3. Expt 21: Fashion MNIST
4. Expt 22: Polynomial curve fitting
5. Expt 23: Instrumenting CNN



**Unsupervised Learning**
    * Clustering
    * Supervised vis-a-vis Unsupervised
    * What if we remove all labels?
    * Unsupervised Clustering -K-Means
    * K-Means
        * So how do we choose the right K


**Hierarchical Clustering**
    * Top-down
    * Bottom-Up
    * Single-Link Algorith

**Deep Learning Frameworks**
    * Keras, PyTorch, Theano, TensorFlow, Caffe2, mxnet, Chainer, MSFT CNTK, Gluon
    * PyTorch
    * Basic Operations in PyTorch
    * Neural Networks in PyTorch

---














## 4th May 2019

**Mini-Hackathon**

Classify a given pair of stackoverflow posts, as duplicate, direct-link, indirect-link or unrelated. The features will be the word2vec average representation of the two posts, and the label will 4 possibilities mentioned above.

The following activities as a part of this larger problem:
1. Using pre-trained Word2Vec model, to get a word2vec representation of the 'massaged' stackoverflow data (i.e. no preprocessing would be required)
2. Building classifiers using SKLearn and reporting accuracies.
3. We have provided an architecture such that the entire data can be clustered, and classifiers can run on each cluster using multithreading. Your task is to only create a KMeans clustering definition using SKLearn, and plug it at the location asked.


---


## 5th May 2019

Lectures:
1. Lecture 13: Random Forests, Ensemble Techniques
2. Lecture 14: Support Vector Machines
3. Lecture 15: Time Series/RNN
4. Lecture 16: Human in the Loop Systems



**Ensemble Methods**
    * Bagging: Bootstrap Aggregation
    * Boosting Illustration
    * DI: Random Selected Samples
    * Random Forest Classifier


**Support Vector Machines**
    * Perception Learning
    * Margin: The No-mans Band
    * Svm Non-Linear

**Sequential Data and Learning**
    * Sequential Data Examples
    * Time Series
    * Time series prediction
    * Performance Metrics For Time Series Data


**RNNs**
    * The network predicts using only current sample
    * Why RNNs
    * Generating poetry with RNNs

**Human in the Loop**
    * Different Roles for Human in the Loop
    * Relevance Feedback
    * Rocchio Model


---




## 11th May 2019

Experiments:
1. Expt 24: SVM, SVM with kernels
2. Expt 25: Face recognition with SVM
3. Expt 26: Random Forests, Ensemble Methods
4. Expt 27: Weather Prediction
5. Expt 28: Rocchio's algorithm


---


## 12th May 2019

Experiments:
1. Expt 29: Movie Recommendation system KNN
2. Expt 30: Movie Recommendation system SVD KNN
3. Expt 31: Alexa Chatbot

**Recommendation Systems**
    * Recommendation Systems Everywhere
    * Types of Recommendation Systems
    * User-based CF Algorithm
    * Enhancing CF with Friends
    * Item-Based Nearest Neighbor Algorithms
    * Hybrid Recommendation Methods
    * Netflix Movie Recommender
    * Social Recommender Systems
    * Collaborative Filtering

**Time Series Modelling**
    * NAIVE MODELS
    * The technique can be adjusted to take trend into consideration:
        * Simple Averages
        * Moving Averages
    * Exponential smoothing
    * Stationary series
    * Why care about stationarity of a time series?
    * Making a series stationary
    * Approaches for Univariate time series models
    * Box-Jenkins Models
        * Box-Jenkins Model Identification
     
**Deployment of ML solutions**
    * Qualities of a Classifier
    * Practical Issues when applying Machine Learning Models
        * Overfitting
        * Clean Data
        * Normalization, Discretization
        * Missing Values
        * Cost-Sensitive Learning
        * Lack of Data



---






## M3: Deep Learning and Practical Issues
    * Introduction of Deep Learning and Toolchain
    * Convolutional Neural Networks
    * Auto-Encoders
    * Recurrent Neural Networks
    * Overview of Advance Topics
    * Human in the Loop Solutions, Deployment


---


## 18th May 2019

* Demystifying Chatbot

**Hackathon**: Alexa Chatbot to Suggest a laptop
* Understand an existing Alexa chatbot

Follow all of the following steps in sequence:
1. Setting up Your Alexa Skill in the Developer Console
2. Setting Up A Lambda Function Using Amazon Web Services
    1. Login to sandbox and activate virtual env
    2. Go to http://aws.amazon.com and sign in to the console
    3. Choose "Services" at the top of the screen, and type "Lambda" in the search box.
    4. Check your AWS region
    5. Configure your aws access
    6. Click the "Create a Lambda function" button
    7. Click on "Author from scratch" .
    8. Configure your trigger
    9. Finish configuring your function
    10. Now go to your Lambda function and select “ Upload a file from Amazon S3 ”
    11.(Optional) Click the Configure test events dropdown menu on the top of the page.
    12. Select 'Alexa Start Session' from the 'Event Template' dropdown.
    13. Type LaunchRequest into the 'Event Name' field.
    14. Click the orange 'Create' button at the bottom of the page
    15. Click the Test button at the top of the page. 1. You should see a light green box with the message: Execution result: succeeded at the top of the page.
    16. Copy the ARN value from the top right
3. Connecting Your Voice User Interface To Your Lambda Function
4. Testing Your Alexa Skill
5. Customize the Skill to be Yours



---


## 19th May 2019

Lectures:
1. Lecture 17: Convolutional Neural Networks;
2. Lecture 18: Autoencoders Lexture
3. Lecture 19: Appreciating CNNs
4. Lecture 20: RNN, LSTM, GRU

**CNNs**
    * Convolution Operation
    * Stride
    * Padding
    * Evolution of Learning
    * Convolution layer: Different Possibilities
    * Layer wise abstraction
    * Max Pooling
    * AlexNet Architecture
    * HIERARCHICAL CONVOLUTIONS
    * Convolutional Neural Networks for Sentence
    * NLP with CNN
    * Visualizing CNNs
    * Transfer Learning 
    * 

**Autoencoders**
    * Deep Auto-encoder



**RNNs**
    * Introduction to RNN/LSTM
    * RNN basic architecture
    * Neurons with Memory
    * Weather Prediction
    * Sentence Level Author Identification
    * Generating poetry with RNNs

---










## 25th May 2019

Experiments:
1. Expt 32: Transfer learning and Finetuning
2. Expt 33: Visualization of CNNs

---


## 26th May 2019

Experiments:
1. Expt 37: Uniform and Non Uniform Quantizations;
2. Expt 38: Student and Teacher Networks;
3. Expt 39: Weight Intializations and updates


Pruning
    * Big Huge Neural Network!
    * Why Pruning?
    * Model Compression
    * TYPES OF PRUNING:
        * Fine Pruning : Prune the weights
        * Coarse Pruning : Prune neurons and layers
        * Static Pruning : Pruning after training
        * Dynamic Pruning : Pruning during training time
    
    * Neuron Pruning
        * Dropping Neurons by Regularization
    * QUANTIZATION
        * Binary Quantization
        * 8-bit uniform quantization
        * Non Uniform Quantization/ Weight Sharing
        * Weight Sharing while Training
        * Deep Compression by Song Han
        * Product Quantization
        * Residual Quantization
    
Student – Teacher Networks
    * GoogLe Net
    * Grouped Convolutions
    * MobileNet
    * ShuffleNet
    * MobileNetV2




---











## 1st June 2019
    * Mini-Hackathon

---


## 2nd June 2019

Lectures:
1. Lecture 21: Beyond AlexNet
2. Lecture 22: BP Revisited
3. Lecture 23: Siamese Networks 
4. Lecture 24: GANs


---












## 8st June 2019
Experiments:
1. Expt 40: Siamese
2. Expt 41: GAN Tutorial from PyTorch
3. Expt 42: Tuning Hyperparameter learning rate
4. Expt 43: Tuning hyperparamter optimizer _ Adam
5. Expt 44: Hackathon debrief

---


## 9th June 2019
    * Hackathon

---