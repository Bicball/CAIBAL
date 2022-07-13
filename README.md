CAIBAL
=====

A python implementation of *CAIBAL - Cluster-Attribute Interdependency Based Automatic Labeler* <sup>1</sup>. 

Abstract---Clustering is a relevant research area in Machine Learning. The purpose of clustering is to group the objects in a dataset so that each group is made up of similar ones, which have characteristics that make them groupable, and between different groups a degree of dissimilarity is essential. The process of interpretation of the groups is fundamental to the pratical applicability of clustering. Automatic labeling, as defined in this research, results in tuples composed of attributes and their respective ranges of values. Each cluster must have a number of tuples capable of providing a unique identification for all objects, so that they are distinguishable from each other by different representative attributes or ranges of different values for the same attribute. This paper presents an unsupervised clusters labeling method that employs the CAIM (Class-Attribute Interdependency Maximization) discretization algorithm in order to find representative value ranges in the attributes that will be relevant for clusters interpretation. The model in this research sought to obtain a method that mitigates the limitations observed in other works that proposed automatic labeling of clusters. The tests carried out with 03 databases - Seeds, Iris and Glass - result in an average accuracy of the suggested labels of 97.20%. The labels suggested are made up of few attributes, compared with previous labelers, and in most cases one attribute is sufficient to define it.

[1] *"Marcel Moura, Rodrigo Veras, and Vinicius Machado. 2022. CAIBAL: cluster-attribute interdependency based automatic labeler. In Proceedings of the 37th ACM/SIGAPP Symposium on Applied Computing (SAC '22). Association for Computing Machinery, New York, NY, USA, 1109–1116. https://doi.org/10.1145/3477314.3507140"*
[https://dl.acm.org/doi/abs/10.1145/3477314.3507140](https://dl.acm.org/doi/abs/10.1145/3477314.3507140)
