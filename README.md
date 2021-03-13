# POS-Tagging
Classifying word and its POS tag

## Tooling

- Python
  - Numpy 
  - Pandas
  - Sklearn
  - Tensorflow
  - Word2Vec

## Concepts 

- ML concepts 
  - Natural Language Processing
  - Embeddings 
  - RNN and LSTM Models 
  
## Steps

1. The Statements are converted into words(tokenized) and then mapped to relative indexes using tensorflow library. 
2. Padding is done to ensure **uniform input length**.(As models are not able to handle variable input lenght)
3. Embeddings is a way to compare words on the basis of more than one parameters,therefore word2vec model is loaded and embeddings weights are created for words that are present in word2vec dictionary.
4. LSTM model is made the summary of whose is shown in the notebook.
5. Inverse mapping function is made to handle raw user input to feed to model and generate valid output.

Head over to the [notebook](https://github.com/RheagalFire/POS-Tagging/blob/main/Part-of-Speech-Tagging.ipynb) to get a brief about the code of above listed instructions.
