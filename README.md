.

📂 Project Structure
FakeNewsClassifier/
│── FakeNewsClassifierUsingLSTM.ipynb   # Jupyter Notebook (main project)
│── dataset.csv                         # Dataset (news headlines/articles with labels)
│── requirements.txt                    # Dependencies (TensorFlow, Keras, etc.)
│── README.md                           # Project documentation

⚙️ Features

Uses Natural Language Processing (NLP) for text preprocessing

Implements LSTM (RNN) for sequence learning

Trains on labeled dataset of Fake vs Real news

Achieves high accuracy in classification

End-to-end workflow in a single Jupyter Notebook

📊 Dataset

The dataset contains:

News text/headlines

Labels:

1 → Real News

0 → Fake News

(You can replace with datasets from Kaggle Fake News Dataset
 or other sources.)

🚀 How to Run

Clone the repository

git clone https://github.com/yourusername/FakeNewsClassifier.git
cd FakeNewsClassifier


Install dependencies

pip install -r requirements.txt


Open Jupyter Notebook

jupyter notebook FakeNewsClassifierUsingLSTM.ipynb


Run all cells to:

Load and preprocess data

Tokenize and pad sequences

Build & train LSTM model

Evaluate on test dataset

🧠 Model Architecture

Embedding Layer (word vector representation)

LSTM Layer (sequence learning)

Dense Layers (classification)

Sigmoid Output (binary classification: FAKE / REAL)

📈 Evaluation

Metrics: Accuracy, Precision, Recall, F1-score

Loss Function: Binary Crossentropy

Optimizer: Adam
