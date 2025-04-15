# Transformer-Neural-Network
Code Transformer neural network components piece by piece. 

I've learned and explained each components of Transfomer in diffrent notebooks 1-6.
Notebook 7_Transformer_10k_rows_E2E contains end to end run but with 10k rows. Not good enough amount of data to train a Transformer translator.

I am using MAC PRO M3 14core GPU and 18GB RAM, to process the massive data with getting out of memory error and utilize the cores efficiently I had to break the dataset in chunks.

I pulled a dataset from kaggle: https://www.kaggle.com/datasets/preetviradiya/english-hindi-dataset

Notebook 8 contains the pre-processing steps(cleaning data, creating vocabs etc....) and Notebook 9 contains batch processing, training the model and translation of ENGLISH to HINDI language 

In Notebook 9, I have broken down the entire dataset in smaller chunks to train the model by feeding chunks one after another via for loop. Each chunk is further broken in batches for efficient and fast training on MAC.

Model at least learned something. Need better cleaning of data and better english-hindi sentences dataset