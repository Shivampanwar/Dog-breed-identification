# Dog Breed Identification

Given an image of a dog,  algorithm will identify an estimate of the canine’s breed out of total 133 dog's breed.


### Prerequisites

Keras, Tensorflow, Jupyter notebook, Python 2.7



### Installing

Download data from https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip and make a folder called  dogImages inside main project and extract files from given link iside this folder itself. 

Make a folder called 'bottleneck_features' inside main project. Download data from https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz and keep it inside 'bottleneck_features' folder. 

If you want to make bottleneck features see, 'Making Bottleneck.ipynb' . Since, making bottleneck features is a computationally heavy task it is recommended to use bootleneck features directly.


## Running the tests

Run Dog breed identification.ipynb  for checking results.  You can use pretrained weights saved inside saved_models directory and model_architecture_vgg_self_made.json to directly run model with weights without training.

### Results
![image](https://user-images.githubusercontent.com/12275601/40762728-87a97b0e-64bf-11e8-9043-5b43952f0415.png)









