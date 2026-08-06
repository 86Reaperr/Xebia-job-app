# 📄 Resume-Based Job Recommender

An AI-powered Resume-Based Job Recommendation System built with **Python** and **Streamlit**. The application analyzes a user's resume, extracts key skills, and recommends the most relevant job along with a direct LinkedIn application link.

## 🚀 Live Demo

**Try the deployed application here:**

👉 **https://huggingface.co/spaces/86reaperr/resume-job-app**

---

## ✨ Features

- 📄 Upload resumes in PDF format
- 👤 Automatically extracts candidate name
- 🛠 Extracts technical skills from the resume
- 🤖 Recommends the best matching job
- 🔗 Provides a direct LinkedIn application link
- ⚡ Clean and interactive Streamlit interface

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- Scikit-learn
- PyPDF2
- PyMuPDF
- NLTK
- Regex

---

## 📂 Project Structure

```
Resume-Job-Recommender/
│
├── app.py
├── preprocess.py
├── train.py
├── requirements.txt
├── data/
│   └── jobs_dataset_with_features.csv
├── utils/
│   ├── extract.py
│   └── recommend.py
└── README.md
```

---

## 📦 Installation

### Clone the repository

```bash
git clone https://github.com/86Reaperr/Resume-Job-Recommender.git
cd Resume-Job-Recommender
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
streamlit run app.py
```

---

## 📋 Requirements

```
streamlit
scikit-learn
pandas
PyPDF2
nltk
regex
PyMuPDF
```

---

## 💡 How It Works

1. Upload your resume (PDF).
2. The application extracts text from the resume.
3. Candidate name is identified.
4. Technical skills are extracted.
5. Skills are matched against the job dataset.
6. The highest-ranked job recommendation is displayed with a LinkedIn application link.

---

## 🌟 Future Improvements

- Recommend Top 5 matching jobs
- Support DOCX resumes
- Resume score analysis
- Skill proficiency detection
- Multi-platform job links ( Indeed, Naukri)

---

## 👨‍💻 Author

**Pranav Sharma**

B.Tech Computer Science Engineering (AI & ML)

---

## 📜 License

This project is intended for educational and learning purposes.
