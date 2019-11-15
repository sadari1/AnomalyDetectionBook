# AnomalyDetectionBook
Code for Beginning Anomaly Detection Using Python-Based Deep Learning

The book can be found at: 
https://www.amazon.com/Beginning-Anomaly-Detection-Python-Based-Learning/dp/1484251768

and

https://www.apress.com/gp/book/9781484251768


My contributions to the book are chapters 1,2,3,5,7, appendix A, and appendix B.

The relevant code:

**Chapter 7: Encoder-decoder TCN Credit card-supervised.ipynb**
  A temporal convolutional network (one dimensional CNN with causal padding and with dilation) trained and tested on the credit   card dataset in a supervised manner (classification task)

**Chapter 2: Isolation Forest KDDCUP 1999 final.ipynb**
  Isolation Forest trained on all http data points in the KDDCUP 1999 dataset in an unsupervised manner.
  
**Chapter 3: Keras MNIST CNN.ipynb**
  A standard CNN trained on MNIST in Keras.
  
**Appendix A: Keras code.ipynb**
  Various tensor operations in Keras as well as an example of a CNN applied to MNIST using the sequential format. 
   
**Chapter 2: OCSVM KDDCUP 1999.ipynb**
  A One Class Support Vector Machine applied to the KDDCUP 1999 http data points in a semi-supervised manner (train on normal, evaluate on a novelty set)
  
**Appendix B: PyTorch .ipynb**
  Tensor operations, an example of a CNN in PyTorch applied to MNIST in a refined format (defining train and test functions for example), as well as how to define models in PyTorch in a sequential and a ModuleList format.
  
**Chapter 3: PyTorch MNIST CNN.ipynb**
  Standard CNN applied to MNIST in PyTorch.
  
**Chapter 5: RBM on credit card final.ipynb**
  Restricted Boltzmann Machine applied to the credit card dataset.
  
**Chapter 5: RBM on kddcup final.ipynb**
  Restricted Boltzmann Machine applied to the KDDCUP 1999 http data points.
  
**Appendix B: TCN Pytorch Credit Card Final.ipynb**
  A Temporal Convolutional Network (similar to the TCN in "TCN on credit card.ipynb", which was done in Keras) created using the PyTorch framework and applied to the credit card dataset.
  
**Chapter 7: TCN on credit card.ipynb**
  A Temporal Convolutional Network created in Keras applied to the credit card dataset
