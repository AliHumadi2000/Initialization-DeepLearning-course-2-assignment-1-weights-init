# Initialization-DeepLearning-course-2-assignment-1-weights-init
### Welcome to the first assignment of Course 2 of the Deep Learning Specialization!  Training your neural network requires specifying an initial value of the weights. A well-chosen initialization method helps the learning process.  In this notebook, you'll try out a few different initializations and see how they lead to different results. 
Initialization
Welcome to the first assignment of Improving Deep Neural Networks!

Training your neural network requires specifying an initial value of the weights. A well-chosen initialization method helps the learning process.

If you completed the previous course of this specialization, you probably followed the instructions for weight initialization, and seen that it's worked pretty well so far. But how do you choose the initialization for a new neural network? In this notebook, you'll try out a few different initializations, including random, zeros, and He initialization, and see how each leads to different results.

A well-chosen initialization can:

Speed up the convergence of gradient descent
Increase the odds of gradient descent converging to a lower training (and generalization) error
Let's get started!

Important Note on Submission to the AutoGrader
Before submitting your assignment to the AutoGrader, please make sure you are not doing the following:

You have not added any extra print statement(s) in the assignment.
You have not added any extra code cell(s) in the assignment.
You have not changed any of the function parameters.
You are not using any global variables inside your graded exercises. Unless specifically instructed to do so, please refrain from it and use the local variables instead.
You are not changing the assignment code where it is not required, like creating extra variables.
If you do any of the following, you will get something like, Grader not found (or similarly unexpected) error upon submitting your assignment. Before asking for help/debugging the errors in your assignment, check for these first. If this is the case, and you don't remember the changes you have made, you can get a fresh copy of the assignment by following these instructions.

Table of Contents
1 - Packages
2 - Loading the Dataset
3 - Neural Network Model
4 - Zero Initialization
Exercise 1 - initialize_parameters_zeros
5 - Random Initialization
Exercise 2 - initialize_parameters_random
6 - He Initialization
Exercise 3 - initialize_parameters_he
7 - Conclusions
