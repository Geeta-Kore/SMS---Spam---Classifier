# Email/SMS Spam Classifier

A **Streamlit** web application to classify messages as **Spam** or **Not Spam** using **NLTK** for text preprocessing and a **TF-IDF + Multinomial Naive Bayes** machine learning model.

---

## Features
- Text preprocessing: lowercasing, tokenization, stopword removal, and stemming.
- Classifies messages as **Spam** or **Not Spam**.
- User-friendly web interface built with Streamlit.

---

## Installation & Usage

Clone the repository, install dependencies, and run the app:

```bash
git clone https://github.com/your-username/spam-classifier.git
cd spam-classifier
python -m venv .venv
# Activate virtual environment:
# Windows
.\.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
