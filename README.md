# Fake News Detection with Machine Learning

##  What's the Project About?

In today’s world, it's hard to tell which news is real and which is fake. So, I built a small machine learning model that can help detect fake news automatically.

The model takes in news content — like headlines or articles — and predicts whether it's **REAL** or **FAKE** using text analysis and pattern recognition. It was trained using real-world data, and all of this is wrapped up in a single Python file to keep things simple and clear.

---

##  Objectives

- Build a model that can differentiate between real and fake news articles.
- Apply basic NLP techniques like cleaning text, removing stopwords, and vectorization.
- Train and test a machine learning model and measure its accuracy.

---

##  What I Did

- Loaded a dataset containing labeled news (`REAL` or `FAKE`).
- Cleaned up the text by removing links, punctuation, and common stopwords.
- Converted the cleaned text into numbers using **TF-IDF Vectorization**.
- Trained a **Passive Aggressive Classifier**, which is fast and well-suited for text classification tasks.
- Evaluated the model to check how well it performs on unseen data.

---

##  Tools and Technologies Used

- **Python** for implementation  
- **Pandas** for data handling  
- **NLTK** for text preprocessing  
- **Scikit-learn** for vectorization, modeling, and evaluation  
- **PassiveAggressiveClassifier** — an efficient linear model perfect for binary classification

---

##  Dataset Format

The dataset (`fake_or_real_news.csv`) should contain:

- `text`: The news article/content  
- `label`: Either `FAKE` or `REAL`
- 
---

## How to Run the Project

1. Clone the repo or copy the Python file.
2. Make sure you have the required libraries:

