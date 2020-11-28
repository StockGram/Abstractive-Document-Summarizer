# Abstractive-Document-Summarizer
The main idea behind creating this model is to generate short and coherent versions of numerous financial reports (10-Ks, 10-Qs). This model is developed mainly for quantitative researchers/portfolio managers who spent numerous hours poring over financial reports in order to manage portfolios. The idea is that a framework that can summarize financial reports with *increased factual correctness* can actually be used in production by quantitative researchers and save numerous hours. 

For this, StockGram has build two types of summarization models: LSTM/Bi-LSTM based NLG model, Encoder-decoder summarization model with attention. 

## LSTM/Bi-LSTM based model for summarizing documents using Natural Language Generation

### Overview

StockGram leverages bi-directional LSTM cells that allows a recurrent system to make its prediction based on both past and future word sequences and hence predicts the next word in the sequence more precisely. The proposed model utilizes custom word-embeddings, *GloVe*, which incorporates global statistics to generate vector representations of news articles in an unsupervised manner and allows the model to converge faster. 

### System Architecture

### Code

The jupyter notebook for leveraging 

### Research Paper


## Encoder Decoder architecture for document summarization

### Overview

### System Architecture

### Code

### Research Paper
