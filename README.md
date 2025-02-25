# AI Powered Resume Screener and Candidate Ranking System

The AI Resume Screening & Candidate Ranking System is a Streamlit-based web application that automates the recruitment process by evaluating and ranking resumes against a given job description. Using Natural Language Processing (NLP) and Machine Learning, the system identifies the most relevant candidates by analyzing resume content and computing similarity scores.

## 🔍 Key Features

## ✅ Automated Resume Parsing

Extracts text from multiple PDF resumes using PyPDF2 (or enhanced with pdfplumber for scanned PDFs).

Supports multi-file upload for bulk processing.


## ✅ AI-Powered Resume Ranking

Uses TF-IDF (Term Frequency-Inverse Document Frequency) to convert text into numerical vectors.

Computes Cosine Similarity to rank resumes based on job description relevance.

Can be upgraded to BERT-based ranking for better semantic matching.



## ✅ Interactive Web UI with Streamlit

Simple & user-friendly drag-and-drop interface.

Displays ranked results in a sortable table.

Allows searching and filtering based on similarity score.



## ✅ Scalable & Robust

Handles large datasets with parallel processing.

Supports OCR for scanned PDFs (via Tesseract).

Ensures efficient memory usage to process large files.



## ✅ Downloadable Reports & Email Notifications (Advanced)

Exports ranked resumes as CSV/PDF reports.

Can integrate email alerts to notify recruiters of the top candidates.



## 🛠️ Tech Stack

Frontend: Streamlit (Python-based UI framework)

Backend: Python (with Pandas, Scikit-Learn, NLP libraries)

Machine Learning: TF-IDF, Cosine Similarity (optional: BERT for better NLP)

File Handling: PyPDF2 (or pdfplumber for better PDF text extraction)

Deployment: Can be hosted on AWS/GCP/Streamlit Sharing


## 🚀 Future Enhancements

🔹 BERT or GPT-powered Resume Analysis for deeper job-resume matching.

🔹 Skill Extraction using Named Entity Recognition (NER).

🔹 Job Matching Recommendation System using AI.

🔹 Graphical Insights (Pie Charts, Bar Graphs) for HR teams.

## 🎯 Ideal Use Cases

Recruiters & HR Teams looking for an automated way to filter candidates.

Job Portals integrating AI-powered resume screening.

Companies & Startups for quick hiring decisions.


This project makes hiring faster, smarter, and more efficient with AI! 🚀
