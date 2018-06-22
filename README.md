# Neural-Language-Translation

Tamil to English translation using Neural Networks

The Neural Translation has been done using Neural network various architectures

### GRU:

Gated recurrent units (GRUs) are a gating mechanism in recurrent neural networks, introduced in 2014 by Kyunghyun Cho et al. Their performance on polyphonic music modeling and speech signal modeling was found to be similar to that of long short-term memory (LSTM). However, GRUs have been shown to exhibit better performance on smaller datasets.

They have fewer parameters than LSTM, as they lack an output gate.

![alt GRU](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT40y8e1AyGtWneAlHeNjCahIxQPYuhrHhb5IRoCkE1lbnECm90)

### LSTM with embedding layer:

The Embedding layer is used to create word vectors for incoming words. It sits between the input and the LSTM layer, i.e. the output of the Embedding layer is the input to the LSTM layer.

The weights for the Embedding layer can either be initialized with random values, or more commonly, they are initialized with third-party word embeddings such as word2vec, GloVe or fasttext (or others) and these weights can optionally be fine-tuned during training. Using third party embeddings to build word vectors is as a form of transfer learning, since you transfer the semantic information between words that was learned during the embedding process.

### Bidirectional LSTM

Bidirectional LSTMs are an extension of traditional LSTMs that can improve model performance on sequence classification problems.

In problems where all timesteps of the input sequence are available, Bidirectional LSTMs train two instead of one LSTMs on the input sequence. The first on the input sequence as-is and the second on a reversed copy of the input sequence. This can provide additional context to the network and result in faster and even fuller learning on the problem.

The idea of Bidirectional Recurrent Neural Networks (RNNs) is straightforward.
It involves duplicating the first recurrent layer in the network so that there are now two layers side-by-side, then providing the input sequence as-is as input to the first layer and providing a reversed copy of the input sequence to the second.

![alt LSTM](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQSSlc4T67JL1OlnN7mLAmGQr6I1Xj-9f7H1XUp2odfXPh1mmW8)




