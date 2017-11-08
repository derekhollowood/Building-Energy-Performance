# Building Energy Performance

This repository contains a Jupyter notebook that was made to test out different machine learning techniques on an interesting data set. I first ran into this dataset on UC Irvine's machine learning repository. The dataset was created by Angeliki Xifara and was processed by Athanasios Tsanas.

Quick Overview of the data:
The goal is to perform a regression analysis to predict the energy efficiency of different building types from labeled data. For the inputs, 12 different building shapes were generated using the application Ecotect. Then using the application NODEM, simulations were performed to predict the heating and cooling load for each building shape, while also varying three other parameters: orientation, glazing area, and glazing area distribution (the latter two variables describe the enclosure's transparence, provided by windows). The raw data provided consists of the input data for these simulations, along with their outputs. However, instead of specifying the exact building shape, five features associated to building shape are given. They are relative compactness, surface area, wall area, roof area, and overall height. The purpose of this project is to train a machine learning model which can predict the heating and cooling load for a building type solely based on the eight input features (and not relying on expensive simulations).

The analysis carried out follows chapter two of Aurélien Géron's Hands-On Machine Learning with Scikit-Learn and TensorFlow.

Bibliography

A. Tsanas, A. Xifara: "Accurate Quantitative Estimation of Energy Performance of Residential Buildings using Statistical Machine Learning Tools", Energy and Buildings, Vol. 49, pp. 560-567, 2012

Géron, Aurélien. Hands-on Machine Learning with Scikit-Learn and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems. O'Reilly, 2017.
