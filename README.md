🎬 IMDB Sentiment Analysis Using Deep Learning


🔍 Project Overview

This project focuses on building a deep learning model to perform binary sentiment classification (positive or negative) on movie reviews from the IMDB dataset. Using Natural Language Processing (NLP) techniques and deep neural networks, the model learns to understand sentiment in textual data. This is a classic text classification problem and has wide applications in opinion mining, review analysis, and recommendation systems.

💡 Key Features

->Uses the IMDB movie reviews dataset from Keras Datasets.

->Performs text preprocessing using tokenization and padding.

->Builds a deep learning model with:

    o Embedding layer

    o Bidirectional LSTM layer

    o Dropout and Dense layers

->Trains the model to classify reviews as positive or negative.

->Includes early stopping and model evaluation on test data.

->Deployed via a Streamlit web app for real-time sentiment prediction of user-input reviews.

🧠 Model Architecture

->Embedding Layer: Converts words into dense vector representations.

->Bidirectional LSTM: Captures dependencies from both past and future contexts.

->Dropout Layer: Prevents overfitting.

->Dense Layers: Final classification layer using sigmoid activation.
