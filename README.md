# Spam Classifier

This project is a Spam Classifier. It takes a set of words and searches it within the body of the email after normalizing it. If found, it classifies it as a Spam with 99.897% accuracy. 
Support Vector Machine(SVM) has been used to train the algorithm do train on the set of examples.

This code is written in Octave but can run on both Octave and Matlab.

To refine the calculations of the regularization parameter, the training set has been divided into 3 sets:
1. Training
2. Test
3. Cross Validation set.

To run the code, simply run the file ex6_spam.m in Octave or Matlab.
