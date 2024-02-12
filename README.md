# Multiclass classification of news articles

## Description

The text-mining project aims at building a supervised machine learning model for categorizing news articles. It explores the use of sparse and dense feature representations, the requisite text preprocessing for each, and various combinations of supervised classification techniques for this multi-class text classification task. The dataset
which has been used for this investigation contains news headlines and short descriptions from the Huffington Post, for news articles published from the years 2012 to 2022.

This dataset is in JSON format with labeled categories like ‘Politics’, ‘Sports’, and ‘Arts’ which can be used for supervised learning. For example, one of the rows is:

<img width="700" alt="image" src="https://github.com/ShrutiRavichandran/Multiclass-classification-of-news-articles/assets/47455312/0e62f098-f050-4463-a203-91b9d4dce3b9">


For more details on the experiments, please refer to the following files:
- File 1
- File 2
- File 3

## Prerequisites
The dataset can be downloaded from Kaggle: https://www.kaggle.com/datasets/rmisra/news-category-dataset

This project uses a pretrained Glove word embeddings (glove.6B.zip) in one of the experiments which can be downloaded from https://nlp.stanford.edu/projects/glove/ 

Rest of the models have been trained during the course of this project on the Huffington Post dataset. Given the limitations on the fize size on Github, the trained model pickle files could not be added here, but the jupyter notebooks contain the code for training the model as well.

## Instructions on running the code
This project has been completely undertaken in jupyter notebooks. The notebooks can be downloaded and run locally, or uploaded to google colab if better computational resources are required.

There are some experiments that train neural network models using Tensorflow/Pytorch. It is recommended to upload the file to google colab and use a GPU to execute these sections as local compute resources would most likley not be powerful enough.
