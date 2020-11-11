<h1 align="center">
  <a href=#>
    <img src="https://github.com/zalandoresearch/fashion-mnist/blob/master/doc/img/embedding.gif" width="50%"/>
  </a>  
  <br>
  Fashion MNIST Classifier
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vcwild/fashion-mnist-classifier">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/vcwild/fashion-mnist-classifier">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
  <a>
</p>

## Implementation
- [Original model](image_classifier.ipynb)
- [Underlying features](image_classifier_underlying.ipynb)

## Scoring

### With 1 dense layer

Overall accuracy: 0.7950

### With 2 dense layers

Baseline accuracy: 0.8484\
Best validation accuracy: 0.8640 

## How this neural network is structured?

### Input, output and hidden layers 

<p align='left'>
  
  <img src='http://i.imgur.com/WonDKDM.png' alt='layers' />

</p>

## Summary
### Model

Type: "sequential"

|Layer (type)|Output Shape|Param #  | 
|---|---|---|
flatten (Flatten) |            (None, 784) |              0       
dense (Dense) |                (None, 256) |              200960    
dense_1 (Dense) |             (None, 128) |              32896     
dropout (Dropout) |            (None, 128) |              0         
dense_2 (Dense) |              (None, 10) |               1290      

Total params: 235,146\
Trainable params: 235,146\
Non-trainable params: 0  

### Optimizer

Adam (SGD)\
Adam optimization is a stochastic gradient descent method that is based on adaptive estimation of first-order and second-order moments.

### Loss Function

Sparse categorical crossentropy

## References
Xiao, H. *et al*. [Fashion MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist). GitHub; 2015.\
Sampaio, C. Deep Learning. AOVS Sistemas de Informática S.A; 2019.\
Chollet, F. *et al*. [Keras](https://keras.io/api/). GitHub; 2015.
