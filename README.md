### Newswire classification
***Newswire classification*** is a multi-class classification problem. That uses the ***Reuters*** dataset for classification. A denely connected neural network with ***ReLu*** activation function for the input and the hidden layer and ***sigmoid*** function has been used for the final output layer.

### Reuters dataset 
This is a dataset of 11,228 newswires from Reuters, labeled over 46 topics. This was originally generated by parsing and preprocessing the classic Reuters-21578 dataset, but the preprocessing code is no longer packaged with Keras. Each newswire is encoded as a list of word indexes (integers). For convenience, words are indexed by overall frequency in the dataset, so that for instance the integer "3" encodes the 3rd most frequent word in the data. This allows for quick filtering operations such as: "only consider the top 10,000 most common words, but eliminate the top 20 most common words".
As a convention, "0" does not stand for a specific word, but instead is used to encode any unknown word.
