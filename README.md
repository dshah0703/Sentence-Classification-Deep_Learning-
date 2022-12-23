Overview:
•	Going to replicate the deep learning model behind the 2017 paper PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstract 
•	When it was released, the paper presented a new dataset called PubMed 200k RCT which consists of ~200,000 labelled Randomized Controlled Trial (RCT) Abstract. 
•	The goal of the dataset was to explore the ability of NLP models to classify sentences which appear in sequential order.
•	Problem in the sentence:  The number of RCT papers released is continuing to increase, those without structed abstracts can be hard to read and in turn slow down researchers moving through the literature
•	Solution in the sentence: Create an NLP and deep learning model to classify abstract sentences into the role they play (e.g., objective, methods, results, conclusion etc) to enable researchers to skim through the literature (hence Sentence Classification 😎) and dive deeper when necessary
•	In this project, converting the dataset from dictionary to dataframe format and applying preprocessing steps such as OneHotEncoder, LabelEncoder  and applying text into list
•	Created 4 different models where the Baseline Model 1: Consist of multinomial Naïve Base Model. Also Implemented Text Vectorization and Text Embedding also Character Embedding.
•	Model 2: Contains Convolution 1D with token embeddings, Model 3: contains Feature Extraction with pre-trained token embedding. The last Model 4: was Pre-trained Model + Char Embedding + Positional Embedding
•	Lastly, we observed the results of all four models and evaluated those models and made a prediction. 



Dependent External Libraries:

1.	os
2.	pandas
3.	OneHotEncoder
4.	LabelEncoder
5.	TfidfVectorizer
6.	MultinomialNB
7.	Pipeline
8.	accuracy_score
9.	precision_score
10.	recall_score 
11.	f1_score
12.	numpy
13.	tensorflow
14.	layers
15.	matplotlib.pyplot
16.	TextVectorization
17.	plot_model
18.	tensorflow_hub
19.	random
20.	string
21.	English


Retrieve/Execution:

We fetched the dataset from Kaggle. Here’s the link:
https://www.kaggle.com/datasets/anshulmehtakaggl/200000-abstracts-for-seq-sentence-classification

We are using the google colab platform to execute our code in steps.
