# Neural Networks

## Intro

Learning objectives:
* Create a simple deep neural network.
* Tune the hyperparameters for a simple deep neural network.

Data set:
The dataset for this exercise is based on 1990 census data from California. The dataset is old but still provides a great opportunity to learn about machine learning programming.

## Usage

### Running code cells
You must run code cells in order. In other words, you may only run a code cell once all the code cells preceding it have already been run.

To run a code cell:

1. Place the cursor anywhere inside the [ ] area at the top left of a code cell. The area inside the [ ] will display an arrow.
2. Click the arrow.
Alternatively, you may invoke Runtime->Run all. Note, though, that some of the code cells will fail because not all the coding is complete.

### Why did you see an error?
If a code cell returns an error when you run it, consider two common problems:

1. You didn't run all of the code cells preceding the current code cell.
2. If the code cell is labeled as a Task, then you haven't written the necessary code.

### Use the right version of TensorFlow
The following hidden code cell ensures that the Colab will run on TensorFlow 2.X, which is the most recent version of TensorFlow:
```python 
%tensorflow_version 2.x
```
## Definition

### 1. Build and train a model function
* ```create_model(my_learning_rate, feature_layer)```, which tells TensorFlow to build a linear regression model and to use the `feature_layer_as_fp` as the representation of the model's features.

* ```train_model(model, dataset, epochs, label_name, batch_size)```, which will ultimately train the model from training set examples.

### 2. Plotting function
* ```plot_the_loss_curve(epochs, rmse)```,a loss curve.

## Document

Google LLC 2020
