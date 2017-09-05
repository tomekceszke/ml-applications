
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
- Hypothesis x->hθ(x)->predicted y
    - hθ(x)=θ0+θ1x1+θ2x2+θ3x3+⋯+θnxn
    - https://www.desmos.com/calculator/ccrnfxvreb
- Cost function: accuracy of hypothesis function, also called "Squared error function" or "Mean squared error"
- Minimization methods of cost function:
    - [gradient descent](https://www.youtube.com/watch?v=WnqQrPNYz5Q),
        - feature scaling and mean normalization: −1 ≤ x(i) ≤ 1
        - learning rate α
    - [normal equation](https://www.youtube.com/watch?v=N4d_9GQ9QFc),
        - https://en.wikipedia.org/wiki/Linear_least_squares_(mathematics)
    - Conjugate gradient, BFGS, L-BFGS
- F-score, r-square
- underfitting, overfitting, bias, variance, ...
- regularization

#### Linear: 
- Example: [Car Price Prediction](https://github.com/tomekceszke/car-price-prediction)
#### Polynomial: 
- New features from old ones
- Example: [Gas consumption forecast](https://github.com/tomekceszke/gas-consumption-forecast) 
### Classification
- Prediction vs classification
- y∈{0,1} - Binary Classification Problem
#### Logistic regression:
- Hypothesis: 0≤hθ(x)≤1
    - https://www.desmos.com/calculator/kzk1lwvryl
    - hθ(x)=g(θ0+θ1x1+θ2x2+θ3x3+⋯+θnxn)
    - z=θ0+θ1x1+θ2x2+θ3x3+⋯+θnxn
    - g(z) = 1/(1+e^-z) - [sigmoid](https://en.wikipedia.org/wiki/Sigmoid_function)
- Decision boundary - the line that separates the area where y = 0 and where y = 1.
    - hθ(x)≥0.5→y=1
    - hθ(x)<0.5→y=0
    - g(z)≥0.5 when z≥0
- Cost function
    - J(θ)=−1/m∑i=1m[y(i)log(hθ(x(i)))+(1−y(i))log(1−hθ(x(i)))]
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
