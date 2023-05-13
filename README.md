# Vector-Space-Model
Python implementation of a document retrieval system using tf-idf weights with the SMART notation of lnc.ltc for ranking and fetching the most relevant documents based on a given query. The system is built in Python and designed to be used in Google Colab.
Information retrieval is a fundamental task in natural language processing and text analysis. The goal is to retrieve the most relevant documents from a large collection based on a user's query. One popular approach for document retrieval is using tf-idf (term frequency-inverse document frequency) weighting, which calculates the importance of a term in a document relative to its occurrence in the entire document collection.

The SMART notation of lnc.ltc is a specific weighting scheme that can be used with tf-idf to rank and retrieve documents. The notation stands for:
lnc: logarithmically scaled term frequency with no document frequency weighting
ltc: logarithmically scaled term frequency with cosine normalization
