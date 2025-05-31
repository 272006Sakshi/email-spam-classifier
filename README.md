# email-spam-classifier
A simple yet effective machine learning model that classifies emails as Spam or Not Spam (Ham) using Multinomial Naive Bayes and TF-IDF vectorization. Built using Python and scikit-learn.

# 📧 Email Spam Classifier using Multinomial Naive Bayes

This project is a **machine learning model** built to classify emails as **Spam** or **Not Spam (Ham)** using **Multinomial Naive Bayes** and **TF-IDF vectorization**. It serves as a basic example of text classification using NLP techniques.

---

## 🧠 Features

- Preprocesses email text: lowercasing, punctuation removal, stopwords removal
- Converts text data into numerical format using **TF-IDF**
- Trains a **Multinomial Naive Bayes** classifier
- Predicts whether an email is spam or not
- Shows classification report & accuracy

---

## 📁 Dataset

The project uses a labeled dataset containing spam and ham messages.  
Example:

| Label | Message                      |
|-------|------------------------------|
| ham   | "Hey, how are you?"          |
| spam  | "Congratulations! You won!"  |

---

## 📦 Libraries Used

- `pandas`
- `scikit-learn`
- `matplotlib` (optional for visualization)

---

## 🛠️ How It Works

1. **Load the dataset**
2. **Preprocess the text** (tokenization, cleaning, etc.)
3. **Convert text to vectors** using `TfidfVectorizer`
4. **Train** the Multinomial Naive Bayes model
5. **Evaluate** the model using accuracy & classification report
6. **Predict** whether new messages are spam or not

---

## 🚀 Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/email-spam-classifier.git
   cd email-spam-classifier

