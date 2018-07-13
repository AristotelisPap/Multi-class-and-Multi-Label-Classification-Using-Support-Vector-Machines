# Multi-class-and-Multi-Label-Classification-Using-Support-Vector-Machines

In this project, we dealt with a Multi-class and Multi-label dataset in which we had to identify the "Family", the "Genus" and the "Species" labels of frogs given some data taken from audio recording.
In order to deal with this problem, we used the Binary Relevance technique and we trained 3 different types of Support Vector Machines (SVM) algorithms:

1) SVM with Gaussian Kernel
2) Linear SVC with L1 regularization
3) Linear SVC with L1 regularization and SMOTE

We also used 10-fold CV in order to tune the hyperparameters of these algorithms.

In the last part of the project, instead of using the Binary Relevance, we applied the Classifiers Chain method combined with a SVM with Gaussian Kernel which showed an additional improvement to the test set accuracy compared to the Binary Relevance method.
