# Multiclass classification of news articles

## Description

The text-mining project aims at building a supervised machine learning model for categorizing news articles. It explores the use of sparse and dense feature representations, the requisite text preprocessing for each, and various combinations of supervised classification techniques for this multi-class text classification task. The dataset
which has been used for this investigation contains news headlines and short descriptions from the Huffington Post, for news articles published from the years 2012 to 2022.

This dataset is in JSON format with labeled categories like ‘Politics’, ‘Sports’, and ‘Arts’ which can be used for supervised learning. For example, one of the rows is:
{
"link":"https://www.huffpost.com/entry/hulu-reboot-should-you-watch-it_n_6324a099
e4b0eac9f4e18b46",
"headline": "'Reboot' Is A Clever And Not Too Navel-Gazey Look Inside TV Reboots",
"category": "CULTURE & ARTS",
"short_description": "Starring Keegan-Michael Key, Judy Greer and Johnny Knoxville, the
Hulu show follows the revival of a fictional early 2000s sitcom.",
"authors": "Marina Fang and Candice Frederick",
"date": "2022-09-20"
}

For more details on the experiments, please refer to the following files:
- File 1
- File 2
- File 3

## Prerequisites
The dataset can be downloaded from <here>

This project uses a pretrained Glove word embeddings obtained from <link> in one of the experiments which needs to be downloaded. 

Rest of the models have been trained during the course of this project on the Huffington Post dataset. Given the limitations on the fize size on Github, the trained model pickle files could not be added here, but the jupyter notebooks contain the code for training the model as well.

