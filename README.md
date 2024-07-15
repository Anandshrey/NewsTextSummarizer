# Extractive News Text Summarizer

## Overview
This repository contains the python code for a News Text Summarizer that creates an Extractive Text Summary from multiple articles on the same news story. 
The program uses the TexRank algorithm for the summarization. 

## Dataset
UCI News aggregator uci-news-aggregator.csv having 422,937 news stories collected by a web aggregator between March 10th, 2014 and August 10th, 2014. 
The dataset is available on Kaggle at https://www.kaggle.com/datasets/uciml/news-aggregator-dataset

## Requirements
If running in a local environment, the following command can be used to install the required packages:

pip install -r requirements.txt


## Sections
This repository is divided into the following sections:

- Load Data
- Create Word Embeddings
- Create Graph of Similarity Matrix Scores
- Create Extractive Summary using Top-ranked Pages in the Graph
