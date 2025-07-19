# ResumeChecker
# 📄 Resume Checker Based on Job Description (JD)

This project helps you analyze your resume by comparing it with a job description (JD). It gives an **ATS score** and suggests the most relevant job roles for your skill set.

## 🚀 Features

- ✅ Extracts text from uploaded resume PDFs
- 🔍 Extracts and filters keywords from Job Descriptions
- 🧠 Matches your skills against 10 pre-defined job roles:
  - AI/ML Intern
  - Data Analyst
  - Web Developer
  - Backend Developer
  - Cloud Engineer
  - DevOps Engineer
  - Cybersecurity Analyst
  - Data Scientist
  - Business Analyst
  - Full Stack Developer
- 📊 Generates a pie chart showing your ATS match score
- 📋 Displays suggestions to improve your resume

## 🛠️ Tech Stack

- Python
- Gradio
- Tesseract OCR (via `pytesseract`)
- PyMuPDF (`fitz`)
- pdf2image
- NLTK
- Matplotlib

## 📦 Installation

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils
