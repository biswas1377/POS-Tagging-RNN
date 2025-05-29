This project explores and compares the performance of different Recurrent Neural Network (RNN) architectures—including Simple RNN, LSTM, GRU, and BiLSTM for Part-of-Speech (POS) tagging in natural language processing. We analyze these models under various configurations and training conditions, both with and without Word2Vec embeddings.

Features:

Exploratory Data Analysis (EDA) on POS-tagged datasets

Data preprocessing with tokenization, padding, and encoding

Model training with multiple RNN architectures using Keras

Integration of custom and Word2Vec embeddings

Hyperparameter tuning and model comparison


Visualization of performance metrics including:

Loss curves

Confusion matrices

Accuracy and Macro F1-score comparisons


Key Insights:

BiLSTM generally outperforms other models, especially when trained with Word2Vec embeddings.

Overfitting is observed at higher epochs without embedding regularization.

Macro F1-score is used for evaluation due to class imbalance in POS tags.
