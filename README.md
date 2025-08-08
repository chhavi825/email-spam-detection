📧 Email Spam Detection using Machine Learning
This project is a machine learning application that classifies SMS messages as **Spam** or **Ham (not spam)** using Natural Language Processing (NLP) and various classification algorithms.

---

🔍 Objective
To build and evaluate a model that accurately detects whether an SMS message is spam based on its content.

---

🗂️ Dataset

- Source: [UCI SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)
- Format: Tab-separated text file with two columns:
  - `label`: `spam` or `ham`
  - `message`: the content of the SMS

---

🧪 Machine Learning Models Used

- ✅ Logistic Regression  
- ✅ Naive Bayes  
- ✅ Random Forest Classifier  

All models are trained and evaluated using **TF-IDF** feature extraction and a **train-test split**.

---

🛠️ Technologies & Libraries

- Python
- Pandas
- scikit-learn
- re, string
- TfidfVectorizer

---

🧼 Text Preprocessing Steps

1. Lowercasing
2. Removing numbers
3. Removing punctuation
4. Removing extra spaces
5. Stopword removal (handled by `TfidfVectorizer`)

---

🧠 Model Training Workflow

```python
# Load dataset
# Clean text
# Transform text using TF-IDF
# Split into training and testing
# Train multiple classifiers
# Evaluate performance
# Predict on new messages


