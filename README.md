# SPAM Detector App

The **Spam Detector** is a web application built with Python and Streamlit. It classifies email and SMS messages as **Spam** or **Not Spam** using a machine learning model. The application leverages the **NLTK library** for natural language processing and a pre-trained **Multinomial Naive Bayes model** for classification. The dataset I used to train the model can be found here: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

## Features
- Preprocesses user input text (removes stopwords, punctuation, and performs stemming).
- Vectorizes text input using a pre-trained **TF-IDF Vectorizer**.
- Predicts whether the input message is spam or not using a trained **Multinomial Naive Bayes model**.
- User-friendly interface powered by **Streamlit**.

---

## Files in the Project
1. `app.py` - The main application file for running the Streamlit web app.
2. `model.pkl` - Pre-trained **Naive Bayes** model for spam detection.
3. `vectorizer.pkl` - Pre-trained **TF-IDF Vectorizer** for text transformation.
4. `README.md` - Documentation file for the project.
5. `nltk_data` - Directory containing the required NLTK resources.

---

## Installation

Follow these steps to set up and run the project on your local machine or AWS EC2 instance:

### Prerequisites
- Python 3.9 or higher.
- Pip (Python package manager).
- Access to the NLTK data required by the app (`punkt` tokenizer).

### Step 1: Clone the Repository

git clone https://github.com/abdulcodes0174/Spam_Detector_Web_App.git
cd Spam_Detector_Web_App```

### Step 2:
pip install streamlit nltk sklearn

### Step 3:

python3
>>> import nltk
>>> nltk.download('punkt')
>>> exit()

### Step 4:

streamlit run app.py

