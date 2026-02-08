# FUTURE_ML_03 
**NLP-Based Intelligent Hiring Assistant | Internship & Resume Ready Project**

---

## 🚀 Project Overview
This project builds an **AI-powered Resume Screening System** that automatically ranks candidates based on their similarity to a given job description.  

The system:  
- Extracts resume text from a ZIP dataset  
- Cleans and preprocesses text using NLP techniques  
- Uses TF-IDF vectorization  
- Computes cosine similarity between resumes and job description  
- Ranks candidates by relevance score  
- Identifies matched and missing skills  

This solution simulates a real-world automated hiring assistant used in modern recruitment systems.

---

## 🎯 Business Problem
Recruiters often receive hundreds or thousands of resumes for a single job posting.  

**Manual screening challenges:**  
- ❌ Time-consuming  
- ❌ Subjective  
- ❌ Prone to human bias  

This system automates:  
- 📊 Resume scoring  
- 🏆 Candidate ranking  
- 🧠 Skill gap identification  

Helping HR teams make faster and more data-driven decisions.

---

## 📂 Dataset
**File Used:** `resume.csv.zip`  

Inside ZIP: `Resume/Resume.csv`  

**Key Columns:**  
| Column         | Description                 |
|----------------|----------------------------|
| Resume_str     | Resume text                 |
| Category       | Candidate domain (optional) |

The system dynamically detects the correct resume text column.

---

## 🧹 Text Preprocessing
Text cleaning includes:  
- Lowercasing  
- Removing special characters  
- Removing non-alphabetic characters  
- Stopword removal (NLTK)  

This ensures clean and standardized input for similarity comparison.

---

## 🧠 Methodology

### 1️⃣ Job Description Definition
- Define a custom job description (e.g., Machine Learning Engineer)

### 2️⃣ TF-IDF Vectorization
- Converts text into numerical feature vectors  
- Max features: 5000  
- Captures important keywords

### 3️⃣ Cosine Similarity
- Measures similarity between **Job Description ↔ Each Resume**  
- Generates a similarity score for ranking candidates

### 🏆 Candidate Ranking
- Candidates are sorted in descending order based on similarity score  
- The system displays:  
  - Category  
  - Similarity Score  
  - Matched Skills  
  - Missing Skills  
- Top 10 candidates are printed and saved

### 🛠 Skill Matching System
**Predefined skills list:**  
Python, Machine Learning, Deep Learning, NLP, SQL, Data Analysis, TensorFlow, Keras, Pandas, NumPy  

The system:  
- Extracts matched skills from each resume  
- Identifies missing skills compared to job requirements  
- Adds explainability to candidate ranking

---

## 💾 Output
**Top 10 ranked resumes** are saved as:  
`ranked_resumes_output.csv`

This file contains:  
- Resume details  
- Similarity scores  
- Matched skills  
- Missing skills

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- NLTK  
- Scikit-learn  
- TF-IDF Vectorizer  
- Cosine Similarity  

---

## 🏗 Project Workflow
1. Load dataset from ZIP  
2. Identify resume text column  
3. Clean text using NLP techniques  
4. Define job description  
5. Apply TF-IDF vectorization  
6. Compute cosine similarity  
7. Rank candidates  
8. Extract skills  
9. Save ranked output  

---

## 📈 Skills Demonstrated
- Natural Language Processing (NLP)  
- Text Cleaning & Stopword Removal  
- TF-IDF Feature Engineering  
- Cosine Similarity  
- Resume Ranking Algorithms  
- Skill Gap Analysis  
- Real-world AI for Recruitment  

---

## 🔥 Future Enhancements
- Add semantic embeddings (Word2Vec / BERT)  
- Build interactive dashboard (Streamlit)  
- Add multi-job comparison support  
- Implement weighted skill scoring  
- Deploy as an HR recruitment API  

---

## 🏆 Conclusion
This project demonstrates how NLP and similarity-based algorithms can **automate resume screening and candidate ranking**. By combining TF-IDF vectorization, cosine similarity, and skill matching, the system provides **transparent, data-driven hiring support** and reflects practical AI applications in HR-tech and recruitment automation.



