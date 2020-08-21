# Relevance_based_word_embeddings
This project implements the Relevance based word embeddings introduced by Hamed Zamani in [this](https://dl.acm.org/doi/10.1145/3077136.3080831) work.

The model is implemented in PyTorch. I have followed the maximum likelihood approach for training word embeddings. The matrix multiplication based hierarchical softmax was implemented to imprve the training time of model. I have used Binary Huffman Tree based hierarchical softmax (given that there are many variants of hierarchical softmax out there).  This model can be used for training word embeddings for the Information Retrieval tasks. They have shown to be performing better than the embeddings trained based on the contextual information like GloVe or Word2Vec. 
