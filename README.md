# AI_Resume_Screening

## 🧠 Overview

**AI_Resume_Screening** is a web-based application built using Streamlit that automates the process of resume screening and candidate ranking. It uses Natural Language Processing (NLP) techniques such as TF-IDF vectorization and cosine similarity to match uploaded resumes against a provided job description.

## 🎯 Features

- Upload and analyze multiple resumes in PDF format.
- Enter a custom job description.
- Automatically rank candidates based on the textual relevance of their resume to the job description.
- Display scores in a user-friendly table using Streamlit.

## 🛠 Technologies Used

- **Frontend**: Streamlit
- **Backend**: Python
- **Libraries**:
  - `PyPDF2` – Extract text from PDF resumes
  - `scikit-learn` – TF-IDF and cosine similarity
  - `pandas` – Tabular data display

## 💡 How It Works

1. User enters a **job description** in the text area.
2. Upload one or more **PDF resumes**.
3. The app extracts text from each resume and computes similarity scores with the job description.
4. Resumes are ranked and displayed in descending order of relevance.

## ▶️ How to Run

### 🔧 Install Dependencies

pip install streamlit PyPDF2 scikit-learn pandas

### 🚀 Launch the App

streamlit run Project01.py

### 🧪 Example Use Case

Use this tool to help HR teams or recruiters quickly sort through large volumes of resumes by relevance, saving time and effort in the candidate shortlisting process.

### ⚠️ Known Issues

scikit-learn import typo: change from sklearn.metrices.pairwise to from sklearn.metrics.pairwise.

cosine_similarity(...).flatter should be corrected to .flatten() for proper functionality.

### 📃 License

This project is licensed under the MIT License.
