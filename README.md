# fake-job-predictions
predicts the fake jobs and alerts the users
# 🕵️‍♂️ Fake Job Detector

A machine learning web app that detects whether a job posting is real or fake based on its content. Built using Streamlit and trained in Google Colab.

---

## 🚀 Project Overview

Online job scams are increasing, and it’s critical to identify suspicious job listings. This project uses **Natural Language Processing (NLP)** and **Machine Learning** to classify job descriptions as either legitimate or fake.

The app is deployed using **Streamlit** and allows users to:
- Input job data manually or via file upload.
- View prediction results.
- Receive email alerts for high-risk (fake) job listings.
- Automatically retrain the model when new data is added.

---

## 🔧 Key Features & Technologies Used

### ✅ Features:
- Upload or enter job listing data.
- Real-time prediction using a trained ML model.
- Word cloud visualizations.
- Email alerts for fake job predictions.
- Automatic model retraining with new data.

### 💡 Tech Stack:
- **Python**
- **Streamlit**
- **Scikit-learn**
- **NLTK / SpaCy**
- **Pandas, NumPy**
- **Google Colab** (for training)
- **Gmail SMTP** (for alerts)
- **Matplotlib / WordCloud** (visualization)

---

## 🛠️ Setup Instructions

### 1. 📁 Clone the Repository
```bash
git clone https://github.com/your-username/fake-job-detector.git
cd fake-job-detector
