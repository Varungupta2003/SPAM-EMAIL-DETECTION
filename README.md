# Spam and Phishing Email Detection System

An end-to-end machine learning system for detecting spam and phishing emails using natural language processing and interpretable classification models.

---

## 📌 Overview

Email-based attacks remain one of the most common security threats. This project implements a **machine learning–driven email classification system** that automatically detects spam and phishing emails based on their textual content.

The system focuses on transparency and reliability by using classical NLP techniques and interpretable models, making it suitable for real-world security and IT support applications.

---

## 🧠 Approach

The pipeline follows a structured, end-to-end workflow:

1. **Data Ingestion** – Load labelled email datasets  
2. **Text Preprocessing** – Cleaning, tokenisation, stop-word removal  
3. **Feature Extraction** – TF-IDF vectorisation  
4. **Model Training** – Logistic Regression classifier  
5. **Model Evaluation** – Precision, Recall, F1-score, Confusion Matrix  
6. **Inference** – Predict spam/phishing vs legitimate emails  

---

## 🛠️ Technologies Used

- Python  
- scikit-learn  
- Pandas & NumPy  
- TF-IDF Vectorisation  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 📊 Evaluation Metrics

The model is evaluated using:
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

These metrics ensure performance is measured accurately, especially for imbalanced datasets common in spam detection tasks.

---

## 📂 Project Structure
├── data/
│ └── email_dataset.csv
├── notebooks/
│ └── spam_detection.ipynb
├── models/
│ └── trained_model.pkl
├── results/
│ └── evaluation_metrics.png
└── README.md


---

## 🎯 Key Features

- Interpretable machine learning model  
- Handles real-world, noisy email text  
- Suitable for security, IT helpdesk, and filtering use cases  
- Clean, modular pipeline design  

---

## 🚀 Future Enhancements

- Add phishing URL and metadata analysis  
- Integrate transformer-based models  
- Deploy as a REST API using FastAPI  
- Real-time email stream classification  

---

## 👤 Author

**Varun Gupta**  
MSc Artificial Intelligence  
University of East London  

📧 Email: varungupta.ml@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/varun-gupta-6311202a7  
💻 GitHub: https://github.com/Varungupta2003

