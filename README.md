
# Mood Detection from Text 🧠💬

This project is an NLP-based machine learning model that predicts the mood or emotion expressed in a given text. It uses text preprocessing techniques and vectorization (TF-IDF) to classify emotions such as happiness, sadness, anger, and more.

## 🎯 Objective

To build a text classification model that can detect the emotional tone (mood) from user-generated textual data using machine learning.

## 🧠 Techniques Used

- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Streamlit for deployment

## 🗂️ Project Structure

```
mood_prediction/
│
├── data/                     # Dataset used for training
├── models/                   # Saved model files
├── app.py                    # Streamlit application
├── mood_prediction.ipynb     # Jupyter notebook for model building
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

## 📝 Dataset

- Type: Text-based emotion detection dataset
- Features: `Text` (input sentence)
- Target: `Mood` (label like Happy, Sad, Angry, etc.)
- Source: Custom or from Kaggle (specify if used)

## 🔍 NLP Preprocessing

- Lowercasing
- Removing punctuation, stopwords
- Tokenization
- TF-IDF Vectorization

## 📈 ML Models Used

- Logistic Regression
- Train-test split evaluation
- Classification metrics: Accuracy

## 💻 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK / spaCy
- Streamlit

## 🚀 How to Run the App

1. Clone the repository:
   ```bash
   git clone https://github.com/swikritsubedi12/mood_prediction.git
   cd mood_prediction
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## 📌 Future Enhancements

- Use deep learning (LSTM, BERT) for better accuracy
- Visualize mood prediction probabilities
- Add support for user input from files or live chats
- Create API endpoints using Flask or FastAPI

## 🙋‍♂️ Author

**Swikrit Subedi**  
📧 swikritsubedi12@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/swikrit-subedi-4913a8340)  
💻 [GitHub](https://github.com/swikritsubedi12?tab=repositories)
🔗 [Streamlit](https://moodprediction-atdcwwdzmzi9mqgcaf5t2h.streamlit.app/)  
---

> This project is a part of my data science portfolio focused on Natural Language Processing (NLP) and machine learning.
