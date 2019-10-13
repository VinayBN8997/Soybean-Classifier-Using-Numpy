# Soybean-Classifier-Using-Numpy

## The MLP model (3 hidden layers) is completely built from scratch using Numpy

## Dataset : Weed Detection in Soybean Crops
### https://www.kaggle.com/fpeccia/weed-detection-in-soybean-crops/download#1008.tif
### This image dataset has 15336 segments, being 3249 of soil, 7376 of soybean, 3520 grass and 1191 of broadleaf weeds. 

The actual data is converted from images to a numpy array for faster processing.
## Numpy Dataset (Customized) : https://drive.google.com/open?id=1eoGZk9De74tKq-hsZCPgdFMnvB4K9eRM

## Training:
```
layer_1 = 1024 neurons
layer_2 = 256 neurons
layer_3 = 32 neurons

epochs = 50
learning rate = 0.001
```
<img width="317" alt="Training Error" src="https://user-images.githubusercontent.com/33830482/66718800-b7f45100-ee05-11e9-804e-6b07f2f2aca0.png">

# Test cases:
<img width="739" alt="Test Images" src="https://user-images.githubusercontent.com/33830482/66718801-b7f45100-ee05-11e9-9f15-12b4e47c0f62.png">

