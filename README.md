# Word-Embeddings
 ### Word2Vec Model
- Word2Vec Google's Pretrained Model
- Contains vector representations of 50 billion words

- Words which are similar in context have similar vectors

- Distance/Similarity between two words can be measured using Cosine Distance
### Applications
- Text Similarity
- Language Translation
- Finding Odd Words
- Word Analogies
### Word Embeddings
- Word embeddings are numerical representation of words, in the form of vectors.

- Word2Vec Model represents each word as 300 Dimensional Vector

- In this tutorial we are going to see how to use pre-trained word2vec model.

- Model size is around 1.5 GB
- We will work using Gensim, which is popular NLP Package.

##### Gensim's Word2Vec Model provides optimum implementation of
1) CBOW Model

2) SkipGram Model

Paper 1 Efficient Estimation of Word Representations in Vector Space

Paper 2 Distributed Representations of Words and Phrases and their Compositionality

### Word2Vec using Gensim
Link https://radimrehurek.com/gensim/models/word2vec.html

### CODE
##### Load Word2Vec Model
KeyedVectors - This object essentially contains the mapping between words and embeddings. After training, it can be used directly to query those embeddings in various ways
