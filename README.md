Objective: Develop machine learning models to classify emotions in text samples.

This notebook follows the assignment requirements: loading and preprocessing, feature extraction, Naive Bayes, Support Vector Machine (SVM), model comparison, and a final conclusion.

The assignment specifically asks for text cleaning, tokenization, stopword removal, CountVectorizer or TfidfVectorizer, Naive Bayes, SVM, and evaluation using metrics such as accuracy and F1-score.
## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Regular Expressions
- NLTK
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## 📚 NLP Techniques Used

### 1. Text Cleaning

The text is cleaned by:

- Converting text to lowercase
- Removing URLs
- Removing unnecessary characters

### 2. Tokenization

Sentences are split into individual words.

### 3. Stopword Removal

Common English words such as:

- the
- is
- a
- and

are removed using NLTK stopwords.

### 4. TF-IDF Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert text into numerical features that machine learning models can understand.

The TF-IDF vectorizer is fitted only on the training data and the same vocabulary is used to transform the testing data.

## 🤖 Machine Learning Models

### Multinomial Naive Bayes

Naive Bayes is a classification algorithm commonly used for text classification.

### Support Vector Machine

A Linear SVM is used because it works well with high-dimensional text features such as TF-IDF.

## 🔄 Project Workflow

Dataset
↓
Data Understanding
↓
Remove Missing Values & Duplicates
↓
Text Preprocessing
↓
Tokenization
↓
Stopword Removal
↓
Train-Test Split
↓
TF-IDF Feature Extraction
↓
Naive Bayes
↓
SVM
↓
Model Evaluation
↓
Model Comparison
↓
Best Model Selection
↓
New Text Prediction

## 📊 Model Evaluation

The models are evaluated using:

- Accuracy
- Weighted F1-score
- Classification Report
- Confusion Matrix

The accuracy and F1-score of both models are compared to identify the better-performing model.

## 🔮 New Text Prediction

The project also allows new text to be entered and classified using the trained models.

Example:

```text
"I am extremely happy today"
