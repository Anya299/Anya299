# 🚀 AI-Powered Resume Screening & Ranking System (ATS Intelligence Tool)

## 📌 Overview

The AI Resume Screening & Ranking System is an intelligent Applicant Tracking System (ATS) that automates resume evaluation by matching candidate resumes with job descriptions using Natural Language Processing (NLP).

It replicates how modern recruitment systems shortlist candidates by analyzing skill relevance, semantic similarity, and missing competencies.

---

## 🎯 Problem Statement

Manual resume screening is:
- Time-consuming
- Prone to bias
- Inconsistent across recruiters

This system solves these issues by:
✔ Automating resume screening  
✔ Ranking candidates based on relevance  
✔ Identifying skill gaps  
✔ Providing data-driven hiring insights  

---

## 🧠 Key Features

### 📄 Resume Processing
- Upload multiple resumes (PDF format)
- Extract and clean text automatically

### 🤖 AI Matching Engine
- TF-IDF vectorization for text representation
- Cosine similarity for ranking resumes
- Job description vs resume semantic matching

### 📊 Skill Intelligence
- Extract key skills from job description
- Match skills with each resume
- Identify missing skills per candidate

### 🖥️ Interactive Web App
- Built using Streamlit
- Real-time resume ranking dashboard
- Simple UI for recruiters and users

---

## ⚙️ System Architecture

Job Description + Resumes
↓
Text Extraction & Cleaning
↓
TF-IDF Vectorization (NLP)
↓
Cosine Similarity Engine
↓
Resume Ranking System
↓
Skill Gap Analysis Module
↓
Streamlit Dashboard


---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Machine Learning:** Scikit-learn  
- **NLP Techniques:** TF-IDF, Cosine Similarity  
- **Data Handling:** Pandas, NumPy  
- **Web Framework:** Streamlit  
- **PDF Processing:** PDFPlumber  

---

## 📂 Project Structure

ai-resume-ranker/
│
├── app.py # Main Streamlit application
├── main.py # Core logic (if used)
├── job_description.txt # Input job description
├── resumes/ # Uploaded resumes folder
├── requirements.txt # Dependencies
└── README.md # Project documentation


---

## 🚀 How It Works

1. User enters job description  
2. Uploads multiple resumes (PDF files)  
3. System extracts text from resumes  
4. TF-IDF converts text into numerical vectors  
5. Cosine similarity calculates match scores  
6. Resumes are ranked automatically  
7. Skill gaps are identified for each candidate  

---

## 📊 Output

- Ranked list of resumes  
- Match score (%) for each candidate  
- Top skills extracted from job description  
- Missing skills per resume  

---

## 🌐 Deployment

This project can be deployed using Streamlit Cloud:

👉 https://share.streamlit.io  

After deployment, you get a live link like:
https://your-app-name.streamlit.app

---

## 💼 Real-World Use Case

This system can be used by:
- HR teams  
- Recruitment agencies  
- Hiring platforms  
- Internship selection systems  

It helps reduce manual screening time by **70–80%** and improves hiring efficiency.

---

## 🔮 Future Improvements

- AI-powered resume feedback using LLMs  
- ATS score prediction model  
- Database integration (PostgreSQL / MongoDB)  
- Resume recommendation system  
- Authentication system for recruiters  

---

## 👨‍💻 Author

**Ananya Shekhar**  
Aspiring AI/ML Engineer  
Focused on building real-world AI systems using Machine Learning and NLP  

---

## ⭐ Key Highlights

✔ Real-world ATS simulation  
✔ NLP-based ranking engine  
✔ Deployable AI web application  
✔ End-to-end ML pipeline  
✔ Industry-relevant problem solving  

---



