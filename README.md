# Mobile Traffic Classification using Deep Learning

The automatic classification of applications and services is an invaluable feature for new generation mobile networks. 

In this project, we propose and validate algorithms to perform this task, at runtime, from the raw physical control channel of an operative mobile network, without having to decode and/or decrypt the transmitted flows. Towards this, we decode Downlink Control Information (DCI) messages carried within the LTE Physical Downlink Control CHannel (PDCCH). DCI messages are sent by the radio cell in clear text and, in this article, are utilized to classify the applications and services executed at the connected mobile terminals. 

Two datasets are collected through a large measurement campaign: one labeled, used to train the classification algorithms, and one unlabeled, collected from four radio cells in the metropolitan area of Barcelona, in Spain. Among other approaches, our Convolutional Neural Network (CNN) classifier provides the highest classification accuracy of 98%. The CNN classifier is then augmented with the capability of rejecting sessions whose patterns do not conform to those learned during the training phase, and is subsequently utilized to attain a fine grained decomposition of the traffic for the four monitored radio cells, in an online and unsupervised fashion.

This is the code repository of the project. You can find more information about it here: https://ieeexplore.ieee.org/abstract/document/9210554
