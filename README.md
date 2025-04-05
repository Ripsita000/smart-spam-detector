# smart-spam-detector
# 📧 Spam Message Detection using Machine Learning

This project focuses on detecting spam messages using machine learning techniques. Two models were implemented: **Logistic Regression** and **Support Vector Machine (SVM)**. The system achieved impressive results with accuracies of **96% (Logistic Regression)** and **98% (SVM)**.

## 🚀 Overview

Spam detection is a common and essential task in natural language processing (NLP). This project leverages machine learning algorithms to classify messages as **spam** or **ham (not spam)** based on their content.

## 🧠 Models Used

- **Logistic Regression**  
- **Support Vector Machine (SVM)**

## 📊 Performance

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 96%      |
| SVM                 | 98%      |

## 🛠️ Features

- Preprocessing of text data (lowercasing, stopword removal, punctuation removal, etc.)
- Feature extraction using TF-IDF vectorization
- Training and evaluation of models
- Performance metrics: Accuracy, Precision, Recall, F1-score

## 🗂️ Project Structure

spam-detection/ │ ├── data/ │ └── spam.csv # Dataset used for training and testing │ ├── notebooks/ │ └── Spam_Detection_Model.ipynb # Jupyter Notebook with full implementation │ ├── models/ │ └── logistic_model.pkl # Trained Logistic Regression model │ └── svm_model.pkl # Trained SVM model │ ├── requirements.txt # List of dependencies ├── README.md # Project documentation └── LICENSE # License file


## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/Ripsita000/spam-message-detection.git
cd spam-message-detection

Install the required packages:
pip install -r requirements.txt
Run the notebook or script to train/test the models.\

## 📁 Dataset

The dataset used in this project is a labeled collection of SMS messages, with two categories: **spam** and **ham** (not spam). It is included in the repository as `spam.csv`, located in the `data/` folder.

**Evaluation**
In addition to accuracy, you can evaluate models using:
**Confusion Matrix**
Precision, Recall, and F1 Score
ROC Curve and AUC Score

**Future Work**
Integration of deep learning models (e.g., LSTM)
Web or mobile application interface for live testing
Dataset expansion for more robust training

🙌 Acknowledgements
Scikit-learn
Pandas
NLTK

📜 License
This project is licensed under the MIT License. See the LICENSE file for more information.



