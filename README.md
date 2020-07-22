# Face recognition using PCA/LBP/LDA
This project was created for the Master of Artificial Intelligence, KU Leuven. It is related to a school project of the Master Course entitled: Biometrics System Concepts,
under the guidance of professor Dirk Vandermeulen.

## Overview
In this project, we test/implement and report about a face recognition algorithm based on 
* Principal Components Analysis (Eigenfaces), 
* Linear Discriminant Analysis (Fisherfaces) and 
* Local Binary Pattern (LBP). 

The performance of the different embedding representations is analyzed on three different datasets:
* Olivetti_faces Database (ATT)
* Labeled Faces in the Wild (LFW)
* CALTECH_faces Database (CALTECH)

The metrics used to compute the pair-wise matching scores are either the Euclidean distance (L2 norm) or Chi-square distance. 
Finally, in a more general classification scenario, we use the feature representations to build more complex classifiers (SVM, KNN, MLP) 
and present their validation results.
