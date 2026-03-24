# 🌍 Language Detection Model (NLP)

> A Machine Learning project that detects the language of a given text using Natural Language Processing techniques in Python.

---

## 🚀 Demo

```python
predict_language("Hola, कैसे हो?")
# Output: Spanish / Hindi (depending on model training)
```

---

## 📖 Overview

This project builds a **Language Detection System** capable of identifying the language of a text input. It leverages **NLP preprocessing** and **machine learning algorithms** to classify text into different languages.

Developed in **Jupyter Notebook**, this project is ideal for learning NLP workflows step by step.

---

## ✨ Features

* 🌐 Detects multiple languages
* ⚡ Fast and lightweight model
* 📊 Uses ML algorithms (Naive Bayes, Logistic Regression, SVM)
* 🧹 Text preprocessing with NLP techniques
* 📓 Beginner-friendly Jupyter Notebook

---

## 🛠️ Tech Stack

* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:**

  * pandas
  * numpy
  * scikit-learn

---

## 📂 Project Structure

```
Language-Detection/
│── language_detection.ipynb   # Main implementation
│── dataset.csv                # Dataset
│── requirements.txt          # Dependencies
│── README.md                 # Documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/language-detection.git
cd language-detection
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Project

```bash
jupyter notebook
```

---

## 📊 Dataset

The dataset consists of text samples labeled with their respective languages.

| Text             | Language |
| ---------------- | -------- |
| Hello world      | English  |
| Hola mundo       | Spanish  |
| Bonjour le monde | French   |

---

## 🔍 Workflow

### 🧹 Data Preprocessing

* Lowercasing
* Removing punctuation
* Tokenization

### 🔠 Feature Extraction

* CountVectorizer
* TF-IDF

### 🤖 Model Training

* Multinomial Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)

### 📈 Evaluation

* Accuracy Score
* Confusion Matrix

---

## 📌 Results

* ✅ High accuracy on test dataset
* ✅ Performs well on short and mixed text
* ⚠️ Slight confusion between similar languages

---

## 🔮 Future Improvements

* 🚀 Deep Learning (LSTM / Transformers)
* 🌍 More language support
* 🌐 Deploy as Web App (Flask / FastAPI)
* 📱 Integrate into mobile apps

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Commit changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements

* Scikit-learn Documentation
* Open-source NLP community
* Public datasets

---

## ⭐ Support

If you like this project, give it a **star ⭐** on GitHub!

---
