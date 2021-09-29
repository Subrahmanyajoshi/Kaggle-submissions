# Simple DNN approach

- A simple Deep Neural Network is used for classification.
- Three types of preprocessing is done on train and test datasets.
  - Replacing nan values with 0.
  - Converting string values into integer values.
  - Min max normalization.
- The same notebook in this directory was submitted. 
- It was able to get 0.77511 score in kaggle.

Model structure:
```shell
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense (Dense)                (None, None, 8)           64        
_________________________________________________________________
dropout (Dropout)            (None, None, 8)           0         
_________________________________________________________________
dense_1 (Dense)              (None, None, 64)          576       
_________________________________________________________________
dense_2 (Dense)              (None, None, 1)           65        
=================================================================
Total params: 705
Trainable params: 705
Non-trainable params: 0
```