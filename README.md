# AI Resume Analyzer

An AI-powered Resume Analyzer built with **Streamlit**, **Python**, **spaCy**, and **PyResParser** that analyzes resumes, extracts important information, recommends skills and courses, calculates a resume score, and provides interview preparation resources.

---

# Features

* Resume Parsing (PDF)
* Extract Name, Email, Phone Number
* Extract Technical Skills
* Candidate Level Detection
* Resume Score Calculation
* Resume Improvement Suggestions
* Domain Prediction
* Skill Recommendations
* Course Recommendations
* Resume Writing Tips
* Interview Preparation Videos
* Resume Preview inside the application

---

# Tech Stack

* Python 3.11
* Streamlit
* spaCy
* PyResParser
* PDFMiner3
* Plotly
* NLTK
* Pandas

---

# Project Structure

```
AI-Resume-Analyser-With-NLP-main/
│
├── App.py
├── Courses.py
├── requirements.txt
├── Logo/
│   └── logo2.png
├── Uploaded_Resumes/
├── README.md
└── sample_resume.pdf
```

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/yourusername/AI-Resume-Analyzer.git

cd AI-Resume-Analyzer
```

---

## Create Virtual Environment

Windows

```bash
python -m venv .venv

.venv\Scripts\activate
```

Linux / Mac

```bash
python3 -m venv .venv

source .venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Install spaCy Model

```bash
python -m spacy download en_core_web_sm
```

---

## Download NLTK Data

```python
import nltk

nltk.download("stopwords")
nltk.download("punkt")
nltk.download("words")
nltk.download("averaged_perceptron_tagger")
nltk.download("maxent_ne_chunker")
nltk.download("omw-1.4")
```

---

# Run the Application

```bash
streamlit run App.py
```

The application will automatically open in your browser.

Default URL:

```
http://localhost:8501
```

---

# Resume Analysis

The system extracts:

* Name
* Email
* Phone Number
* Skills
* Experience Level
* Resume Pages

It also predicts the candidate's preferred field based on detected skills.

---

# Resume Score

The resume score is calculated using the presence of sections like:

* Objective
* Declaration
* Projects
* Achievements
* Hobbies

Each section contributes to the overall score.

---

# Skill Recommendations

Depending on the extracted skills, the application recommends:

* Data Science
* Web Development
* Android Development
* iOS Development
* UI/UX Design

---

# Course Recommendations

Relevant online courses are recommended based on the predicted career domain.

---

# Interview Preparation

The application suggests YouTube videos for:

* Resume Writing
* Interview Preparation

---

# Dependencies

* streamlit
* pandas
* nltk
* spacy
* pyresparser
* pdfminer3
* pillow
* plotly
* streamlit-tags

---

# Removed Dependencies

To improve compatibility and simplify setup:

* MySQL dependency removed
* Pafy dependency removed
* YouTube title fetching simplified

---

# Requirements

* Python 3.11+
* Internet connection (for first-time NLTK and spaCy downloads)

---

# Future Improvements

* SQLite support
* ATS compatibility score
* Resume keyword matching
* Multiple resume comparison
* AI-generated resume suggestions
* LLM-powered career recommendations

---

# Screenshots

Add screenshots of:

* Home Page
* Resume Upload
* Resume Analysis
* Skill Recommendations
* Resume Score
* Course Recommendations

---

# License

This project is intended for educational and learning purposes.

---

# Author

Modified and maintained by:

**Dinesh Kumar VR**

GitHub: https://github.com/DINESHKUMARVR41
