# 📰 AI-Based Fake News Detection Tool

> Detect Fake News using Machine Learning and Natural Language Processing (NLP)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web_App-black?style=for-the-badge&logo=flask)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Scikit--Learn-orange?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-Text_Classification-green?style=for-the-badge)

---

## 🚀 Overview

The **AI-Based Fake News Detection Tool** is a Machine Learning-powered web application that analyzes news articles and predicts whether they are **Fake** or **Real**. The system utilizes Natural Language Processing (NLP) techniques and a trained classification model to provide accurate predictions along with a confidence score.

---

## ✨ Features

- 📰 News Text Input
- 🤖 AI-Based Classification
- ✅ Real News Detection
- ❌ Fake News Detection
- 📊 Confidence Score Output
- 💾 Trained Model Storage
- 🎨 Interactive User Interface
- ⚡ Fast Prediction Response

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend Development |
| Flask | Web Framework |
| Scikit-Learn | Machine Learning |
| Pandas | Data Processing |
| NumPy | Numerical Computation |
| TF-IDF | Text Vectorization |
| HTML/CSS | Frontend Design |

---

## 📂 Project Structure

```text
AI-Fake-News-Detection/
│
├── app.py
├── train_model.py
├── news.csv
├── model.pkl
├── vectorizer.pkl
│
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
└── README.md
```

---

## ⚙️ How It Works

### Step 1
User enters a news article or headline.

### Step 2
The text is preprocessed using NLP techniques.

### Step 3
TF-IDF Vectorizer converts text into numerical features.

### Step 4
The trained Machine Learning model analyzes the content.

### Step 5
The application predicts:

- 🟢 Real News
- 🔴 Fake News

### Step 6
Confidence score is displayed to the user.

---

## 🚀 Installation

### Clone Repository

```bash
git clone <repository-url>
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn flask
```

### Train Model

```bash
python train_model.py
```

### Run Application

```bash
python app.py
```

### Open Browser

```text
http://127.0.0.1:5000
```

---

## 📊 Sample Output

| News Article | Prediction |
|-------------|------------|
| Government launches new education policy | Real News |
| Aliens landed in Mumbai yesterday | Fake News |

---

## 🎯 Future Enhancements

- 🌐 Live News API Integration
- 🧠 Deep Learning Models
- 🌍 Multi-Language Support
- 📈 Analytics Dashboard
- ☁️ Cloud Deployment

---

## 👨‍💻 Author

### Yash Vinchurkar

Passionate about Artificial Intelligence, Machine Learning, and Web Development.

---

### ⭐ If you found this project useful, consider giving it a Star!
