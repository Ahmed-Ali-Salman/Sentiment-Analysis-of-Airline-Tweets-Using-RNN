# Sentiment-Analysis-of-Airline-Tweets-Using-RNN

This project analyzes how travelers expressed their feelings towards major US airlines on Twitter during February 2015. It employs a Long Short-Term Memory (LSTM) recurrent neural network to classify tweets into positive, negative, or neutral sentiments.

## Dataset

The project utilizes the "Twitter US Airline Sentiment" dataset, sourced from Crowdflower's Data for Everyone library. This dataset comprises tweets collected in February 2015, where contributors classified each tweet's sentiment and categorized negative reasons.

## Word Embeddings

The model leverages pre-trained word vectors from the "GloVe: Global Vectors for Word Representation" dataset. These vectors, trained on Wikipedia 2014 and Gigaword 5 corpora, capture word co-occurrence and semantic relationships. This project utilizes the 50-dimensional GloVe embeddings.

## Model

The core of the project is an LSTM network implemented using Keras. This network processes word embeddings, incorporates dropout layers for regularization, and utilizes the Adam optimizer with categorical cross-entropy loss for training.

## Usage

1. Clone the repository.
2. Install the required libraries.
3. Execute the `sentiment-analysis-using-rnn.ipynb` script.

## Contributing

Contributions are encouraged! Feel free to submit pull requests or open issues.

## Acknowledgements

* **Twitter US Airline Sentiment Dataset:** Originally from Crowdflower's Data for Everyone library.
* **GloVe Word Embeddings:** Provided by Jeffrey Pennington, Richard Socher, and Christopher D. Manning. Refer to their paper: "GloVe: Global Vectors for Word Representation" for further information.
