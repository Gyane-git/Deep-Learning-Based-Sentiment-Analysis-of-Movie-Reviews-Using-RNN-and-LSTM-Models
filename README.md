🎬 Sentiment Analysis of Movie Reviews using Deep Learning
This project focuses on sentiment classification of movie reviews (sourced from Twitter posts), using deep learning techniques. The objective is to determine whether a given review conveys a positive or negative sentiment. This is a key task in Natural Language Processing (NLP) with real-world applications in recommendation systems, brand monitoring, and user feedback analysis.


🧠 Models Implemented
Three deep learning models were explored:

Recurrent Neural Network (RNN)
A basic sequence model used for baseline sentiment classification.

Long Short-Term Memory (LSTM)
An improved RNN variant that captures long-range dependencies in text.

Word2Vec + LSTM
Integration of pre-trained Word2Vec embeddings to enhance the model’s understanding of semantic relationships between words.

⚙️ Methodology
Text Preprocessing: Tokenization, lowercasing, stopword removal, padding

Embedding: Word2Vec embeddings were used to convert words into dense vector representations

Training: RNN and LSTM models were trained on pre-processed review data

Evaluation Metric: Accuracy was used to assess model performance

📊 Results
Model	Accuracy
RNN (Baseline)	50%
LSTM	53%
Word2Vec + LSTM	70%

Observation:

LSTM outperformed basic RNN due to its ability to retain longer context.

The Word2Vec embeddings significantly improved the model's performance by enhancing word semantics.

🔍 Key Insights
Word embeddings play a crucial role in improving model performance for sentiment analysis.

While traditional RNNs struggle with long-term dependencies, LSTM models handle them better.

Semantic-rich embeddings like Word2Vec can bridge performance gaps caused by small or sparse datasets.


📈 Future Work
To further improve sentiment prediction accuracy:

Explore more advanced embeddings like GloVe or FastText

Incorporate contextualized embeddings using BERT, RoBERTa, or DistilBERT

Add attention mechanisms or experiment with Transformer-based architectures


🛠️ Requirements
Python 3.8+

TensorFlow / Keras

NumPy

scikit-learn

NLTK / SpaCy

Gensim


📬 Contact
For further information or contributions, reach out to:
Gyanendra Kumar Sah
Email: gyanee750@gmail.com