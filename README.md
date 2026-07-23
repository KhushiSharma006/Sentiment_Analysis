# 📝 Sentiment Analysis using Machine Learning

A Machine Learning project that predicts whether a given text expresses a **Positive** or **Negative** sentiment. The project includes data preprocessing, model training using TF-IDF vectorization, model serialization, and a simple Streamlit web application for real-time sentiment prediction.

---

## 📌 Project Overview

Sentiment Analysis is a Natural Language Processing (NLP) task used to determine the emotional tone behind text. This project uses a machine learning classifier trained on a labeled dataset to classify user input as either **Positive** or **Negative**.

---

## ✨ Features

- 📊 Text preprocessing and cleaning
- 🔤 TF-IDF Vectorization
- 🤖 Machine Learning based sentiment prediction
- 💾 Saved trained model using Pickle
- 🌐 Interactive Streamlit web application
- ⚡ Instant sentiment prediction

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Streamlit
- Pickle

---

## 📂 Project Structure

```
Sentiment_Analysis/
│
├── app.py                     # Streamlit application
├── intro.ipynb                # Data preprocessing & EDA
├── train-Model.ipynb          # Model training notebook
├── sentimentData.csv          # Dataset
├── sentiment_model.pkl        # Trained ML model
├── tfidf_vectorizer.pkl       # Saved TF-IDF vectorizer
├── requirements.txt           # Project dependencies (recommended)
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/KhushiSharma006/Sentiment_Analysis.git
cd Sentiment_Analysis
```

### Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit app using:

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 💡 How It Works

1. User enters a sentence.
2. The input text is cleaned and preprocessed.
3. TF-IDF converts the text into numerical features.
4. The trained Machine Learning model predicts the sentiment.
5. The predicted sentiment is displayed instantly.

---

## 📷 Sample Prediction

**Input**

```
I absolutely loved this movie. The acting was fantastic!
```

**Output**

```
Positive 😊
```

---

**Input**

```
The service was terrible and I am very disappointed.
```

**Output**

```
Negative 😞
```

---

## 📚 Machine Learning Workflow

- Data Collection
- Text Cleaning
- Tokenization
- TF-IDF Vectorization
- Model Training
- Model Evaluation
- Model Serialization
- Streamlit Deployment

---

## 🚀 Future Improvements

- Multi-class sentiment prediction (Positive, Neutral, Negative)
- Deep Learning (LSTM/Bi-LSTM)
- Transformer Models (BERT)
- Emotion Detection
- Confidence Score Display
- Model Deployment on Streamlit Cloud

---

## 👩‍💻 Author

**Khushi Sharma**

- GitHub: https://github.com/KhushiSharma006
- LinkedIn: *(Add your LinkedIn profile here)*

---

## ⭐ If you found this project useful

Please consider giving it a **⭐ Star** on GitHub!
