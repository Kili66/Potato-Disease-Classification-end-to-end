# Tomatoes Disease Classification Project
This is a project build using deep learning precisely CNN algorithm.

# Steps Of The project

* Data Collection: Data are collected from Kaggle. Here is the link: https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf
* After collecting data we explore the data and do some data preprocessing
* The Dataset contains 10 different classes:
 // ['Tomato_Bacterial_spot',
 'Tomato_Early_blight',
 'Tomato_Late_blight',
 'Tomato_Leaf_Mold',
 'Tomato_Septoria_leaf_spot',
 'Tomato_Spider_mites_Two_spotted_spider_mite',
 'Tomato__Target_Spot',
 'Tomato__Tomato_YellowLeaf__Curl_Virus',
 'Tomato__Tomato_mosaic_virus',
 'Tomato_healthy']  //

* for training the model, we apply Convolutional Neural Network(CNN):
          * we apply a filter of 3*3
          * Maxpooling 2*2
          * Flatten
          * Activation function for the hidden layer: reLu
          * Activation function for the output Layer: Softmax
* Model Compiling:
         * Optimizer: adam
         * loss: SparseCategoricalCrossentrop
* model evaluation
* The accuarcy of the model is 0.95
