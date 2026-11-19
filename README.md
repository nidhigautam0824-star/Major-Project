# 📩 SMS Spam Detection Using SVM

## 📌 Project Overview

SMS Spam Detection is a Machine Learning project that identifies whether an SMS message is **Spam** or **Not Spam (Ham)** using the Support Vector Machine (SVM) algorithm.

The project uses Natural Language Processing (NLP) techniques and TF-IDF (Term Frequency-Inverse Document Frequency) to convert text messages into numerical features for classification.

It also includes a user-friendly web application built using Streamlit, where users can enter SMS messages and instantly check whether they are spam or legitimate.

## 🎯 Project Objectives

- To detect spam SMS messages automatically.
- To classify messages into Spam and Not Spam categories.
- To apply Machine Learning techniques for text classification.
- To implement TF-IDF for text feature extraction.
- To develop an interactive web application using Streamlit.

## ✨ Key Features

- **Spam Detection:** Identifies spam and legitimate SMS messages.
- **Machine Learning:** Uses Support Vector Machine (SVM).
- **Text Processing:** Uses TF-IDF vectorization.
- **Interactive Interface:** Simple and user-friendly Streamlit application.
- **Instant Prediction:** Provides classification results for user-entered messages.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Machine Learning | Spam Classification |
| SVM | Classification Algorithm |
| NLP | Text Processing |
| TF-IDF | Feature Extraction |
| Scikit-learn | Machine Learning Library |
| Streamlit | Web Application |
| Pandas | Data Handling |
| NumPy | Numerical Operations |
| Joblib | Saving and Loading Models |

## 📂 Project Structure

```text
SMS-Spam-Detection-using-SVM/
│
├── app/
│   └── main.py
│
├── SMS_Spam_Detector.ipynb
├── spam_data.csv
├── svm_model.pkl
├── tfidf_vectorizer.pkl
├── requirements.txt
└── README.md
```

## ⚙️ How It Works

1. The user enters an SMS message.
2. The input text is processed using the trained TF-IDF vectorizer.
3. The extracted numerical features are passed to the trained SVM model.
4. The model predicts whether the message is Spam or Not Spam.
5. The prediction result is displayed on the Streamlit application.

## 🚀 Installation and Setup

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### Step 2: Open the Project Folder

```bash
cd SMS-Spam-Detection-using-SVM
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Run the Streamlit Application

```bash
streamlit run app/main.py
```

### Step 5: Open in Browser

Open the local URL displayed in your terminal:

```text
http://localhost:8501
```

## 🧪 Example Predictions

**Example 1: Spam Message**

Input:
```text
Congratulations! You have won a free prize. Claim now!
```

Expected Output:
```text
SPAM
```

**Example 2: Normal Message**

Input:
```text
Hey, how are you? Let's meet tomorrow.
```

Expected Output:
```text
NOT SPAM
```

*Note: These are illustrative examples; actual predictions depend on the trained model.*

## 🧠 Machine Learning Algorithm

### Support Vector Machine (SVM)

SVM is a supervised Machine Learning algorithm used for classification tasks. It finds an optimal decision boundary to separate different categories of data.

In this project, SVM is used to classify SMS messages into two categories:

- Spam
- Ham (Not Spam)

### TF-IDF Vectorization

TF-IDF converts text messages into numerical representations so that the Machine Learning model can understand and classify them.

## 📈 Future Improvements

- Email Spam Detection Integration.
- Real-time Email Spam Filtering.
- Support for Multiple Languages.
- Improved Model Performance.
- Spam Detection Dashboard.
- Integration with Gmail API for automatic spam detection.

## 👩‍💻 Author

**Project:** SMS Spam Detection Using SVM

**Domain:** Machine Learning / Artificial Intelligence

**Language:** Python

---

⭐ If you find this project useful, don't forget to give it a star!

**Built with Python, Machine Learning, NLP and Streamlit.**
