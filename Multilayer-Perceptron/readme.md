# Multilayer perceptron

1. [Gaussian_data_numpy.ipynb](https://github.com/Alejandro-ZZ/Deep-Learning/blob/master/Multilayer-Perceptron/Gaussian_data_numpy.ipynb) 

    * Binary classifier using isotropic gaussian samples.

2. [Regression_Boston_Housing_keras.ipynb](https://github.com/Alejandro-ZZ/Deep-Learning/blob/master/Multilayer-Perceptron/Regression_Boston_Housing_keras.ipynb)

    * Regressor using Boston Housing dataset.
    * House price prediction based on 13 features of houses at different locations.
    * K-Fold cross-validation is implemented to train the model.

3. [Multiple_Classification_MNIST_keras.ipynb](https://github.com/Alejandro-ZZ/Deep-Learning/blob/master/Multilayer-Perceptron/Multiple_Classification_MNIST_keras.ipynb)

    * Multiple classifier using MNIST dataset with 28x28 grayscale images of the 10 digits.
    * Prediction of the digit to which a given image corresponds.

4. [Binary_Classification_IMBD_keras.ipynb](https://github.com/Alejandro-ZZ/Deep-Learning/blob/master/Multilayer-Perceptron/Binary_Classification_IMBD_keras.ipynb)

    * Binary classifier using IMBD dataset with movies reviews. 
    * Predicting if a movie review is positive or negative.
    * Four different model are implemented and compared.
    * Learning curves are analyzed to improve the model performance.
    * Used of *Dropout* layers and weight *regularizers*.
    * Implementation of [ReduceLROnPlateau](https://keras.io/api/callbacks/reduce_lr_on_plateau/) callback to reduce learning rate 
    when a metric has stopped improving.
