# 📧 Email Spam Classification Project

## 🚀 Overview

This project uses Natural Language Processing (NLP) and Machine Learning techniques to build an Email Spam Classification system. The classifier is designed to effectively differentiate between spam and legitimate (ham) emails.

## ✨ Features

- 🔍 **Text Preprocessing:** Lowercasing, removing non-alphabetic characters, tokenization, stopword removal, and stemming.
- 📊 **Feature Extraction:** Utilizes TF-IDF (Term Frequency-Inverse Document Frequency) for vectorizing email content.
- 🤖 **Model Training:** Implements the Multinomial Naive Bayes classifier for spam detection.
- 📈 **Evaluation:** Provides performance metrics such as accuracy, classification report, and a confusion matrix visualization.
- 📬 **Real-Time Prediction:** Includes a function to check if a given email is spam or not.

## 📂 Dataset

The dataset used is `spam_email1.csv`, which contains the following columns:

- **📧 label:** Indicates whether the email is 'spam' or 'ham'.
- **📝 text:** The actual content of the email.

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone <https://github.com/dhananjay937/SpamEmail_Classification.git>
   cd email-spam-classification
   ```
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn nltk
   ```
3. Download NLTK stopwords:
   ```python
   import nltk
   nltk.download('stopwords')
   ```

## 💻 Usage

Run the Jupyter Notebook or Python script:

```bash
python spam_detection.ipynb
```

### 📥 Example

```python
email_example = "Congratulations! You've won a $1000 gift card. Click here to claim."
print("Email Classification:", check_spam(email_example))
```

**Output:**

```
Email Classification: Spam
```

## 📁 Project Structure

```
email-spam-classification/
├── spam_detection.py
├── spam_email1.csv
├── README.md
└── requirements.txt
```

## 📊 Performance Metrics

- ✅ **Accuracy:** Measures the overall correctness.
- 📄 **Classification Report:** Includes precision, recall, F1-score.
- 🔢 **Confusion Matrix:** Visualizes true positives, false positives, true negatives, and false negatives.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## 📬 Contact

For queries, feel free to reach out:

- **Email:** [your\_email@example.com](mailto\:patildhananjay1307@gmail.com)
- **LinkedIn:** [Your LinkedIn Profile](www.linkedin.com/in/dhananjay-patil-b25423315)

