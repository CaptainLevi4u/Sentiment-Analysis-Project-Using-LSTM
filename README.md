🚀 Sentiment Analysis on IMDB Reviews using LSTM | Deep Learning Project

I’m excited to share my latest Deep Learning project where I built a Sentiment Analysis Model using a Long Short-Term Memory (LSTM) neural network to classify movie reviews as Positive or Negative.

📌 Project Goal
Leverage Deep Learning techniques in Natural Language Processing (NLP) to accurately predict sentiment from raw text reviews.

🔍 Project Highlights

✅ Text preprocessing (removing stopwords, URLs, lowercasing)
✅ Encoding labels (Positive → 1, Negative → 0)
✅ Tokenization & sequence padding
✅ LSTM architecture with Embedding layer
✅ Dropout for regularization
✅ Early Stopping to prevent overfitting
✅ Data visualization (class distribution & text length distribution)
✅ Model evaluation on unseen test data
✅ Saving trained model & tokenizer for future inference

🛠 Tools & Technologies

Python

Pandas & NumPy

Matplotlib & Seaborn

NLTK

Scikit-learn

TensorFlow / Keras

Pickle

⚙️ Model Architecture

Embedding Layer → LSTM Layer → Dropout → Dense (Sigmoid)

The model was trained using Early Stopping to avoid overfitting and improve generalization.

🎯 Challenges I Faced & How I Solved Them

🔹 1. Overfitting
At first, the model performed very well on training data but slightly worse on validation data.
✔ Solution: Added Dropout layers and implemented Early Stopping.

🔹 2. Handling Variable-Length Text
IMDB reviews have highly variable lengths.
✔ Solution: Applied sequence padding to ensure uniform input size.

🔹 3. Noise in Text Data
URLs, stopwords, and inconsistent formatting affected model performance.
✔ Solution: Applied thorough preprocessing using NLTK and regex cleaning.

🔹 4. Choosing Proper Max Sequence Length
Too short → loss of context.
Too long → unnecessary computation.
✔ Solution: Analyzed text length distribution before selecting max_length.

📊 Results

✔ Strong accuracy on test dataset
✔ Good generalization between training & validation
✔ Clean and reusable pipeline for future NLP tasks

(📸 Check the attached output screenshots for training curves & evaluation metrics.)

🔮 Future Improvements

🚀 Implement Bidirectional LSTM
🚀 Try GRU and compare performance
🚀 Fine-tune a Transformer model (BERT)
🚀 Deploy the model as a REST API
🚀 Build a Streamlit web app for live predictions
🚀 Apply the pipeline to Arabic sentiment datasets

Reusable model for future sentiment analysis tasks.
<img width="1916" height="814" alt="Screenshot 2026-02-27 031534" src="https://github.com/user-attachments/assets/7c3615dc-a782-418a-9572-2b3fedf81eb5" />
<img width="1902" height="862" alt="Screenshot 2026-02-27 031504" src="https://github.com/user-attachments/assets/2b7aa360-bf11-44aa-b446-040ebce1932c" />
<img width="1916" height="853" alt="Screenshot 2026-02-27 031344" src="https://github.com/user-attachments/assets/d47b7d35-dc66-4bd5-be34-ca8503f076ed" />
<img width="1917" height="833" alt="Screenshot 2026-02-27 031311" src="https://github.com/user-attachments/assets/28106158-38ac-4ff7-a479-46ea4f76230b" />
<img width="1444" height="127" alt="Screenshot 2026-02-27 030621" src="https://github.com/user-attachments/assets/ba4e91ea-cc0c-43df-b550-7fc69822c437" />

<img width="576" height="455" alt="train_test" src="https://github.com/user-attachments/assets/da89d50e-c354-4d9f-8529-b37ade7e206a" />
<img width="589" height="455" alt="Sentiment Distribution" src="https://github.com/user-attachments/assets/bc7fbe29-e546-472c-af96-463f92dbf929" />
<img width="704" height="470" alt="Distribution" src="https://github.com/user-attachments/assets/31206ca6-0036-474e-a04f-6688baa2ff28" />


