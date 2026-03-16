# Spam vs Not Spam Text Classification (NLP)

This project builds a **Spam Email Classifier** using **Natural Language Processing (NLP)** and **Neural Networks** to classify messages as **Spam** or **Not Spam (Ham)**.

The model processes text data, cleans it using NLP techniques, and trains a neural network to perform binary classification.

---

## Project Workflow

1. Load Dataset
2. Data Cleaning
3. Text Preprocessing
4. Tokenization
5. Stopword Removal
6. Lemmatization
7. Feature Extraction
8. Machine Learning (DT)
9. Model Training (Neural Network)
10. Model Evaluation

---

## Dataset

The dataset contains SMS/email messages labeled as:

- **Spam**
- **Ham (Not Spam)**

Example:

| Category | Message |
|--------|--------|
| ham | I'm going to attend the meeting |
| spam | Congratulations! You won a free prize |

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- TensorFlow / Keras

---

## NLP Techniques Used

- Tokenization
- Stopword Removal
- Lemmatization
- Text Vectorization

---

## Model

A **Neural Network model** is used to classify messages into:

- Spam
- Not Spam

---

## Visualization

The project also includes visualization of dataset distribution.

Example:

- Spam vs Ham count plot

---

## Conclusion

The Neural Network model successfully classifies messages as spam or not spam.

Key Takeaways:
- NLP preprocessing significantly improves text classification.
- Neural networks can effectively capture patterns in text data.
- The model achieved good performance based on accuracy and F1-score.

Future improvements:
- Use LSTM or Transformer models
- Use larger datasets
- Deploy as a web app

## How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/spam-notspam-text-classification-nlp.git
