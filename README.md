# Motivational and demotivational quotes classification using Keras
Created Neural Network model for the text classification of “Motivational Quotes vs Demotivational Quotes” using Keras

## Microsoft Azure Notebooks
https://notebooks.azure.com/harshit-singhai/projects/quotes-classification

## Dataset Creation: 
Created a dataset of 20 lines of text for class 1: motivational lines (each line
considered as document) and 20 lines of text for class 2: demotivational lines. 20 lines of text
per class and stored them in text file.

## Pre-processing: 
Removed all the stop words (or common words such as a, an, the, for, in etc) and punctuation. Found the unique word list and built
a term frequency matrix.

## Dataset Preparation: 
Split the dataset (75% training and 25% testing) into training and testing
sets with term frequencies as input X, text class (Motivational vs Demotivational) as target
label Y.

## Model Creation: 
Trained a single layer Neural Network model with 32 nodes for 100 epochs.

## Analysis:
1. Ran different single layer Neural Network models with number of nodes as 8, 16, 32,
64, 128, 256, 512 and 1028. 
2. For all the models plotted the number of parameters learned,
training accuracy, testing accuracy and running time for testing in bar chart.
3. Ran different Neural Network models with number of layers as 2, 3, 4, and 5, each
layer with 32 nodes. 
4. For all the models plotted the number of parameters learned,
training accuracy, testing accuracy and running time for testing in bar chart.

## Python packages used
1. Keras
2. NLT
3. Pandas
4. Numpy
5. Matplotlib
