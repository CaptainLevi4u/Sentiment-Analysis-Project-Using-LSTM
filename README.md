# Sentiment-Analysis-Project-Using-LSTM
using a Long Short-Term Memory (LSTM) neural network. The goal is to classify reviews as positive or negative, leveraging deep learning techniques for natural language processing (NLP)
Project Overview:
This project aims to perform sentiment analysis on movie reviews from the IMDB Dataset using a Long Short-Term Memory (LSTM) neural network. The goal is to classify reviews as positive or negative, leveraging deep learning techniques for natural language processing (NLP).

Key Features:

Preprocessing text data by removing stopwords, URLs, and converting text to lowercase.

Encoding sentiment labels (positive → 1, negative → 0).

Splitting data into training and testing sets for evaluation.

Tokenizing text and padding sequences to feed into LSTM.

Building an LSTM model with embedding layers, dropout for regularization, and a sigmoid output layer for binary classification.

Early stopping during training to prevent overfitting.

Visualizing text length distribution, class distribution, and training/validation accuracy.

Evaluating the model on test data to measure performance.

Saving the trained model and tokenizer for future inference.

Tools & Libraries Used:

Python – Programming language

Pandas & Numpy – Data handling and preprocessing

Matplotlib & Seaborn – Visualization

NLTK – Text preprocessing and stopwords removal

Scikit-learn – Train-test split

TensorFlow / Keras – Deep Learning, LSTM implementation

Pickle – Saving trained model and tokenizer

Workflow / Steps:

Load and Explore Dataset: Read the IMDB dataset and check for missing values and duplicates.

Data Cleaning: Remove duplicates, stopwords, and URLs; convert text to lowercase.

Data Visualization: Plot sentiment distribution and text length distribution to understand dataset.

Text Tokenization: Convert text reviews to sequences of integers and pad them to uniform length.

Build LSTM Model: Create a sequential model with embedding layer → LSTM layer → Dense output.

Training: Train the model with early stopping to prevent overfitting.

Evaluation: Test the model on unseen data and compute accuracy and loss.

Save Model & Tokenizer: Persist the trained model and tokenizer for future predictions.

Expected Outcome:

Accurate prediction of movie review sentiment.

Insight into text data distribution and preprocessing effects.

Reusable model for future sentiment analysis tasks.
![Uploading Screenshot 2026-02-26 231910.png…]()
<img width="1902" height="870" alt="Screenshot 2026-02-26 231830" src="https://github.com/user-attachments/assets/973e6866-8f3c-42e4-b9a7-16586816e235" />
<img width="1915" height="873" alt="Screenshot 2026-02-26 231749" src="https://github.com/user-attachments/assets/d0b4a4cc-1b3c-47fd-8c13-adf8787ba3f7" />
<img width="1912" height="867" alt="Screenshot 2026-02-26 231727" src="https://github.com/user-attachments/assets/0b3593ef-74af-4432-8023-0a8bf16d9e81" />
<img width="1444" height="127" alt="Screenshot 2026-02-27 030621" src="https://github.com/user-attachments/assets/76e66adb-f4b5-4f4a-9981-96e3b434f9fd" />
<img width="576" height="455" alt="train_test" src="https://github.com/user-attachments/assets/da89d50e-c354-4d9f-8529-b37ade7e206a" />
<img width="589" height="455" alt="Sentiment Distribution" src="https://github.com/user-attachments/assets/bc7fbe29-e546-472c-af96-463f92dbf929" />
<img width="704" height="470" alt="Distribution" src="https://github.com/user-attachments/assets/31206ca6-0036-474e-a04f-6688baa2ff28" />


