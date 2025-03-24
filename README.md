# AI Resume Screening & Candidate Ranking System

## 📌 Project Overview
This project is an AI-powered Resume Screening and Candidate Ranking System built using **Streamlit, PyPDF2, and Scikit-learn**. It allows users to upload multiple resumes in PDF format, compare them against a given job description, and rank candidates based on **cosine similarity** using **TF-IDF (Term Frequency-Inverse Document Frequency)**.

## 🚀 Features
- Upload multiple resumes in **PDF format**.
- Enter a **job description** manually.
- **TF-IDF Vectorization** and **Cosine Similarity** for ranking resumes.
- **Match Score Boosting** (70%-98%) for more realistic evaluation.
- **Dynamic Resume Ranking** based on similarity score.
- **Improvement Suggestions** to enhance candidate resumes.
- **User-friendly Interface** built with Streamlit.

## 🛠️ Tech Stack
- **Python**
- **Streamlit** (for UI)
- **PyPDF2** (for PDF text extraction)
- **Scikit-learn** (for text vectorization & similarity measurement)
- **Pandas & NumPy** (for data handling & score adjustments)

## 📦 Installation
### Prerequisites
Make sure you have **Python 3.8+** installed on your system.

### 1️⃣ Clone the repository
```bash
git clone https://github.com/LokamHarika/Resume_Ranking/tree/main
cd resume-ranking-system
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app
```bash
streamlit run app.py
```

## 📄 Usage
1. **Upload multiple PDF resumes** using the file uploader.
2. **Enter the job description** in the provided text area.
3. The system will **analyze and rank resumes** based on relevance.
4. View **Match Scores & Ranking**.
5. Click on any resume to get **Improvement Suggestions** for better job alignment.

