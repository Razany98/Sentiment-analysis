Sentiment analysis is a A natural language processing technique used to determine the 
data belongs to which class/type of emotions.  Sentiment analysis 
is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback and understand customer needs.

#### Dataset: 
The dataset contains 20,000 tweets that were collected through API for classifying emotions. 

It contains 6 classes of emotions: 
- Anger 
- joy 
- fear
- love 
- surprise 
- sadness

The dataset can be found at: 
- https://huggingface.co/datasets/dair-ai/emotion 

or 

- https://paperswithcode.com/dataset/emotion 


#### The Pipeline: 
- 1 - Text Preprocessing 
Dataset Cleaning: 
Check for null values 
Check for duplicated values
Remove unwanted patterns as: #, &, punctuation, ... etc. 

- 2 - Text Normalization 
Used NLTK Library and includes 3 Techniques: 
Tokenization: Converting sequence of texts into smaller parts. 
Slemming: Reducing a word to its word stem (root).
Lemmatization: Reduce the word better to its root word, or lemme, good.

- 3 - Word Embedding 
BOW (Bag Of Words): Accuracy 80% 
TF-IDF: Accuracy 77% 
Word2Vec with LSTM: 64% 
- 4 - Modeling & Evaluation 
