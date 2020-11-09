# fashion-mnist-classifier

## How this neural network is structured?

### Input-output and hidden layers 

<p align='left'>
  
  <img src='http://i.imgur.com/WonDKDM.png' alt='layers' />

</p>

## Summary

Model: "sequential"

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

## References
SAMPAIO, C. Deep Learning. <b>AOVS Sistemas de Informática S.A.</b>, <i>[s.l.]</i>. 2019.

