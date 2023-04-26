# CassavaLeafDiseaseClassification

## The Dataset
https://www.kaggle.com/competitions/cassava-leaf-disease-classification/overview

## Setup
Download the dataset and store the csv file of the dataset and json file of the labels in the root directory. Store the images in a folder called train.

## The Code
### ResNet50-resnet50.ipynb
In this notebook, we train a ResNet50 model.

### EfficientNet-50
We lost access to SageMaker before we could push the code for this.

### Vision Transformer - Vision_Transformer.ipynb
In this notebook, we train a Vision Transformer model.

### Ensemble - Ensemble.ipynd
In this notebook, we use the best three models we saved to make inference on the test dataset. We do this by taking the sum of the predictions from the the three models. It results in an accuracy of 86%.

### Hyperparameters Search - project_notebook_parameter_search.ipynb
In this notebook, we perform hyperparameters search for our models.
