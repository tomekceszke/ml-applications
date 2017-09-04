
# Practical applications of Machine Learning

1. [Introduction](#introduction)
1. [Supervised learning](#supervised-learning)
    1. [Regression](#regression)
        1. [Linear](#linear)
        1. [Polynomial](#polynomial)
    1. [Classification](#classification)
        1. [Logistic Regression](#logistic-regression)
        1. [Neural Networks](#neural-networks)
1. [Unsupervised learning](#unsupervised-learning)
    1. [Clustering](#clustering)
        1. [K-means](#k-means)
    1. [Anomaly detection](anomaly-detection)
1. [References](#references)

## Introduction
 > "... computers the ability to learn without being explicitly programmed."

 [Arthur Samuel](https://en.wikipedia.org/wiki/Arthur_Samuel)

## Supervised learning
- (x,y) features, label

### Regression
- Hypothesis: x -> h(x) -> predicted y
- Cost function: accuracy of hypothesis function, also called "Squared error function" or "Mean squared error" https://www.desmos.com/calculator/nyuu7tokie
- Minimization methods of J: [gradient descent](https://en.wikipedia.org/wiki/Gradient_descent), normal equation, ...
- F-score, r-square
- Underfitting, overfitting, bias, variance, ...
- Feature scaling, normalization, regularization
- Learning rate: (α)
#### Linear: 
- Example: [Car Price Prediction](https://github.com/tomekceszke/car-price-prediction)
#### Polynomial: 
- New features from old ones
- Example: [Gas consumption forecast](https://github.com/tomekceszke/gas-consumption-forecast) 
### Classification
- Prediction vs classification
- Decision boundary
#### Logistic regression:
- [Sigmoid](https://en.wikipedia.org/wiki/Sigmoid_function)
- Example: [Traffic light detection](https://github.com/tomekceszke/traffic-light-detection) 
#### Neural Networks
- Neural Networks - explanation
- Back propagation
- Example: [Vehicles counter](https://github.com/tomekceszke/vehicles-counter)

## Unsupervised learning
(x)
### Clustering
#### K-means
- Example: tbd 
### Anomaly detection
- Normal distribution and Gauss function  
- Example: /internal/
## References
### Courses
- Coursera https://www.coursera.org/learn/machine-learning/
- Springboard https://www.springboard.com/learning-paths/machine-learning-python 
### Data sources
- [PL] Dane publiczne https://danepubliczne.gov.pl  
- [PL] https://mojepanstwo.pl/dane
- [PL] GUS http://stat.gov.pl/
- Kaggle https://www.kaggle.com/datasets   
- Google Trends https://trends.google.pl/trends/

### Tools
- Desmos https://www.desmos.com/calculator
- WolframAlpha https://www.wolframalpha.com/

### ML projects
- [My personal projects](https://github.com/tomekceszke?utf8=%E2%9C%93&tab=repositories&q=machine-learning)
- [Where Am I](https://github.com/kootenpv/whereami)
