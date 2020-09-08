# Recurrect Neural Networks

Recurrent neural networks are designed to model sequence, in which the hidden state of the previous step is an input to the current step. The same set of parameter values are applied repeatedly to every steps of the sequence.

## Language Model

* [Predict Next Character with Recurrect Neural Network](https://github.com/msfchen/machine_learning/tree/master/recurrentnn/predictnextchar): [8/13/2020, Coursera NLP Specialization]
  - convert each sentence to a list of character token_ids, ending with EOS_int.
  - a batch data generator, optionally shuffled.
  - Define Gated Recurrent Unit (GRU) model using Trax framework; layers: ShiftRight -> Embedding -> n_layers of GRU -> Dense -> LogSoftmax
  - Train: CrossEntropyLoss, Adam optimizer(0.0005); Validation: CrossEntropyLoss, Accurary; Test Evaluation: Perplexity
  - generating sentence, one predicted next character at a time