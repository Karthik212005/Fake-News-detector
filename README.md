

 📰 Fake News Detection using Machine Learning

 📌 Overview

This project builds a Machine Learning model to classify news articles as **Fake** or **True** using Natural Language Processing (NLP). The system analyzes news text, converts it into numerical features, and predicts whether the information is reliable or misleading.

---

 ⚙️ Features

* Text preprocessing and noise removal
* TF-IDF based feature extraction
* Multiple ML models for comparison
* Manual testing on unseen news samples

---

 📂 Dataset

* **Fake.csv** – Fake news articles
* **True.csv** – Real news articles
* Columns: `title`, `text`, `subject`, `date`

---

 🧠 Workflow

1. Load and merge datasets
2. Clean text (remove punctuation, URLs, special characters)
3. Convert text into TF-IDF vectors
4. Train models and evaluate performance

---

 🤖 Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting

---

 📊 Results

* Logistic Regression achieved around **90% accuracy**
* Model evaluated using Accuracy, Precision, Recall, and F1-Score

---

 🛠️ Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, NLP (TF-IDF)

---

 ▶️ How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

 🚀 Future Improvements

* Use Deep Learning models (LSTM, BERT)
* Deploy as a web application
* Add real-time news prediction


