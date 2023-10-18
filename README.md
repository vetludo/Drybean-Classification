# Neural Network-based Dry Bean Classification

This repository contains the code and results of a simple neural network approach to classify seven different types of dry beans, leveraging the Dry Bean Dataset. The original paper employed an SVM model and achieved a 93.13% accuracy rate in 10-fold cross-validation[^1^][^2^]. In contrast, our neural network approach yielded a slightly better 10-fold average accuracy of 93.14%.

## Dataset Background

The Dry Bean Dataset comprises images of 13,611 grains of 7 different registered dry bean varieties captured using a high-resolution camera. A total of 16 features, including 12 dimensions and 4 shape forms, were extracted from the images[^3^]. Dry beans are a significant agricultural product known for their nutritional value. The dataset aims to foster research towards developing new bean varieties with enhanced nutritional properties and resilience to various adversities like insects, diseases, and drought, while also maintaining or improving the quality of the beans[^4^]. This dataset facilitates the classification of beans based on characteristics such as form, shape, type, and structure, reflecting market considerations[^5^].

## Original Study

The original study utilized a morphological-based model developed for multiclass classification of the dry bean varieties, achieving a classification accuracy rate of 93.13% with an SVM model[^6^][^1^]. The paper titled "Multiclass classification of dry beans using computer vision and machine learning techniques" can be referred to for a detailed understanding.

## Our Approach

We employed a simple neural network model to classify the dry beans, yielding a slightly improved 10-fold average accuracy of 93.14%. The code, model architecture, and evaluation metrics are available in this repository for review and further research.

[^1^]: [Multiclass classification of dry beans using computer vision and machine learning techniques](https://doi.org/10.1016/j.compag.2020.105507)
[^2^]: [Original paper details](https://www.sciencedirect.com/science/article/pii/S0168169920303663)
[^3^]: [Dry Bean Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset)
[^4^]: [Dry Bean Dataset - Michigan State University](https://www.egr.msu.edu/classes/ece848/ece848web/Dry%20Bean%20Dataset.html)
[^5^]: [Dry Bean Dataset | Papers With Code](https://paperswithcode.com/dataset/dry-bean-dataset)
[^6^]: [Original study accuracy rate](https://www.sciencedirect.com/science/article/pii/S0168169920303663)
