# KNN
KNN is used for non-parametric data. It is a Lazy Learner. KNN can be used for classification of data — the output is a class membership that is it predicts a class — a discrete value. An object is classified by a majority vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors. 
Euclidean Distance

DE(x,y)=  ((x1 - y1)^2 + (x2 - y2)^2 +….+ (xn - yn)^2)^1/2    =     (∑(xi - yi)^2)^1/2

#  MKNN
We can make KNN efficient by doing some computational work during training. We had used Modified K-Nearest Neighbor to overcome drawbacks of original KNN classifier, using group prototypes. A group prototype is a prototype of a group of patterns from the same class and falling close to each other by a user defined Euclidean distance d , where 0 ≤ d < 1. There can be multiple group prototypes from the same pattern class. Instead of using training patterns as it is to reason about the testing patterns, these group prototypes are used. This small modification can eliminate all the drawbacks of original KNN.

# OMKNN
Further modifications to MKNN for the optimization purpose and the proposed approach is called OMKNN. The main purpose is to use a m > 1 dimensional vector of distance
parameters for m class training set. The proposed OMKNN approach is expected to further reduce the group prototypes.

# Datasets
 Iris data set available on https://archive.ics.uci.edu/ml/datasets/iris
 Indian Liver Patient data set available on
https://archive.ics.uci.edu/ml/datasets/ILPD+(Indian+Liver+Patient+Dataset)
Diabetic Patient data set available on https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008
