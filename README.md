**A very short project description!**

### Task:
Sentiment analysis of a dataset of tweets using DistilBERT model.

### Dataset:
The data is from Kaggle which can be foudn at this address:  https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis

### Model:
I used as the backbone of my classifier. DistilBERT is a distilled version of the BERT (Bidirectional Encoder Representations from Transformers) model, developed by compressing the original model while retaining its performance, making it more efficient for various natural language processing tasks. The extracted features of the DistilBERT model are then fed into a fully connected neural network for classification.

### Results:
in 10 epochs the model reaches a validation f1 score of 0.93 and test f1 score of 0.97 demonstrating the power of pre-trained language models for NLP tasks.
