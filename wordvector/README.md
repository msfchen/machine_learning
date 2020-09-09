# Word Vectors

Word vectors capture both syntactic and semantic features of words in a dense representation.

* [Train Word Vectors with CBOW Model](https://github.com/msfchen/machine_learning/tree/master/wordvector/cbow): 
  - In continuous bag of words (CBOW) model, we try to predict the center word given a few context words (the words around the center word).
  - A shallow neural network with one hidden layer is used; input is the average of all the one hot vectors of the context words; output is a softmax layer.
  - embs = (W1.T + W2)/2.0

