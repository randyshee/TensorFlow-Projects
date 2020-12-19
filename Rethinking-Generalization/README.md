# Rethinking Generalization
This project is inspired by "Understanding deep learning requires rethinking generalization" (arXiv:1611.03530v2) by Zhang et al. And codes are modification from "Laboratory 2: Computer Vision" of MIT 6.S191: Introduction to Deep Learning.

In this project, I would be trying to reproduce some of the results from Zhang's paper by using MNIST dataset. They found that it's easy for a neural network to remember the train set so the accuracy of the test set would progress to zero with randomization of labels whereas the accuracy of the training set remains high.

Result from the notebook showed that for the models of convolution neural network and fully connect neural network, both the accuracy of train and test set decreased as the randomness increased. However, if the number of epochs was set to an arbitrary large number, we would be able to see similar result to Zhang's. This is because with a large number of epochs, the network could memorize the whole data set (overfitting). Note that the network actually memorize the randomized data set and that's why we should rethink about generalization in deep learning.

© MIT 6.S191: Introduction to Deep Learning
http://introtodeeplearning.com
