# ML-in-chemistry-101
The course materials for "Machine Learning in Chemistry 101"

This graduate-level course in the chemistry department of University of Cambridge gives an overview of the machine learning (ML) tech-
niques that are useful for solving problems in Chemistry, and particularly for
the computational understanding and predictions of materials and molecules at
the atomistic level.
In the first part of the course, after taking a quick refresher of the basic
concepts in Probabilities and Statistics, students will learn about basic and ad-
vanced ML methods including supervised learning and unsupervised learning.
During the second part, the connection between Chemistry and the mathemat-
ical tools of ML will be made, and the concepts on the construction of loss
functions, representations, descriptors and kernels will be introduced. For the
last part, experts who are actively using ML methods to solve research problems
in Chemistry and Materials will be invited to give real world examples on how
did ML methods transformed the way they perform research.

This repository contains the course materials of the part of the lectures given by me (the other parts were given by Lucy Colwell).

The materials cover the following subjects:

* Regression:
+ Linear models, linear regression
+ Polynomial regression
+ Regularization
+ Kernel regression

* Dimensionality reduction

** Curse of the dimensionality

** blessing of non-uniformity

** Prerequisite in Statistics and Mathematics

** Principal component analysis (PCA)

** Non-linear dimensionality reduction methods

* Sparsification

** Single value decomposition (SVD)

** CUR decomposition

** Farthest Point Sampling (FPS)

* Clustering

** Gaussian mixture model (GMM)

** K-means

** DBSCAN

* Representing structual data using SOAP descriptors

For each lecture, there are accomanpying slides, notes, as well as Python notebooks used for practice.

In addition, the folder ml_4_small_molecules contains a challenge: how to use what we learned from the course to predict the formation energies of small molecules.
