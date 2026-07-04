# 📄 Resume Screening System using Machine Learning

## 📌 Project Overview
This project is a Resume Screening System developed as part of my Machine Learning internship.

It uses Natural Language Processing (NLP) techniques to analyze resumes and rank candidates based on their similarity to a given job description.

The system helps automate the recruitment process by reducing manual effort and improving candidate selection efficiency.

---

## 🎯 Objective
- Analyze resumes using NLP
- Compare resumes with job descriptions
- Rank candidates based on relevance
- Identify skill gaps

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Jupyter Notebook

---

## 📊 Dataset Description
The dataset contains resumes with the following columns:
- ID → Unique candidate ID
- Resume_str → Resume text
- Resume_html → HTML format of resume
- Category → Job role category

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Lowercasing text
- Removing special characters
- Removing stopwords

### 2. Feature Extraction
- TF-IDF Vectorization is used to convert text into numerical format

### 3. Similarity Calculation
- Cosine Similarity is used to compare resumes with job description

### 4. Candidate Ranking
- Candidates are ranked based on similarity score

### 5. Skill Gap Analysis
- Required skills are extracted from job description
- Missing and matched skills are identified

---

## 📈 Output
- Ranked candidates list
- Match percentage for each resume
- Recommendation levels:
  - Highly Recommended
  - Recommended
  - Consider
  - Low Match
- Skill gap analysis report
- Output files:
  - ranked_candidates.csv
  - skill_gap_analysis.csv

---


## 📌 Key Learnings
- NLP basics
- TF-IDF Vectorization
- Cosine Similarity
- Text preprocessing
- Resume ranking system

---

## 🚀 Future Improvements
- Improve model accuracy with advanced NLP techniques
- Add deep learning-based matching
- Build a production-level ATS system

---

## 👩‍💻 Author
Fathima Safa MK 

B.Tech ECE  

Aspiring Engineer | Machine Learning Enthusiast  

---

## ⭐ Acknowledgement
This project was completed as part of my Machine Learning internship tasks.
