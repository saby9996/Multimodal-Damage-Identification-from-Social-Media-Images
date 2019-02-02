# Multimodal Damage Identification from Social Media Images

The Repository performs a classification task on the 5879 Images Extracted from the Social Media. As the set of objects in the image is quite diverse and also the set of objects is sparse therefore a huge number of training layers would have been required to develop the model. Therefore, for the task we used the **Inception V3** Pretrained Moel for the Classification Task.

#### Dataset
https://archive.ics.uci.edu/ml/datasets/Multimodal+Damage+Identification+for+Humanitarian+Computing

### Model Archietecture After Using Pretrained Model
```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
inception_v3 (Model)         (None, 2, 2, 2048)        21802784  
_________________________________________________________________
flatten_13 (Flatten)         (None, 8192)              0         
_________________________________________________________________
dense_25 (Dense)             (None, 128)               1048704   
_________________________________________________________________
dense_26 (Dense)             (None, 6)                 774       
=================================================================
Total params: 22,852,262
Trainable params: 22,817,830
Non-trainable params: 34,432
_________________________________________________________________
```
