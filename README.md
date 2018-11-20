# House-Prediction-Model :house:
A tool to predict :house: Prices using Machine Learning (One-Shot).

I wrote a C program that implements simple “one-shot” machine learning algo-rithm for predicting house prices in your area.
For example, the price of the house (y) can depend on certain attributes of the house: number of bedrooms (x1), total size of the house (x2), number of baths (x3), and the year the house was built (x4). Then, the price of the house can be computed by the following equation:
**y=w0 +w1.x1 +w2.x2 +w3.x3 +w4.x4**
Given a house, we know the attributes of the house (i.e., x1, x2, x3, x4). However, we don’t know the weights for these attributes: w0, w1, w2, w3 and w4. The goal of the machine learning algorithm in our context is to learn the weights for the attributes of the house from lots of training data.
