# FUTURE_ML_03
# 📄 Resume Screening & Candidate Ranking System

## 📌 Overview

Recruiters often receive **hundreds of resumes** for a single job role. Manually reviewing each resume is slow, inconsistent, and inefficient.

This project builds a **Machine Learning-based Resume Screening System** that:

* 📂 Analyzes resume text
* 🎯 Matches candidates with a job description
* 📊 Scores and ranks candidates automatically
* ⚠️ Identifies missing skills

👉 This simulates how real **HR-tech platforms** shortlist candidates.

---

## 🚀 Features

* 🧹 Resume text preprocessing (cleaning, stopword removal)
* 🔢 TF-IDF vectorization
* 📐 Cosine similarity scoring
* 🏆 Candidate ranking system
* 🧠 Skill extraction from resumes
* ⚠️ Missing skill detection
* 🔮 Job-role-based matching

---

## 📂 Dataset

Dataset used:
👉 https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset

### Key Column:

* `Resume_str` → Raw resume text

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas, NumPy
* Scikit-learn
* NLTK
* KaggleHub

---

## ⚙️ Installation

```bash id="lg5tx2"
git clone https://github.com/your-username/resume-screening-ml.git
cd resume-screening-ml
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the project:

```bash id="9p2q6u"
python main.py
```

OR use Jupyter Notebook:

```bash id="c9r9hi"
jupyter notebook
```

---

## 📊 Workflow

1. Load resume dataset
2. Clean and preprocess text
3. Input job description
4. Convert text → TF-IDF features
5. Compute similarity (cosine similarity)
6. Rank candidates
7. Extract skills
8. Identify missing skills

---

## 📈 Example

### Job Description:

```id="q3j0au"
Python developer with machine learning and SQL skills
```

### Output:

```id="zx0q7f"
Rank 1
Score: 0.89
Skills: ['python', 'machine learning']
Missing Skills: ['sql']
```

---

## 📉 Output Insights

* Higher score → better job fit
* Missing skills help recruiters identify gaps
* Top candidates can be shortlisted instantly

---

## 📁 Project Structure

```id="qyjx1o"
resume-screening-ml/
│
├── data/
├── main.py / notebook.ipynb
├── requirements.txt
├── README.md
```

---

## 🎯 Future Improvements

* 🔥 Streamlit web app (upload resumes UI)
* 🧠 Use BERT / Transformers for better matching
* 📄 PDF resume parsing
* ⚡ Skill weighting system

---

## 🤝 Contributing

Feel free to fork and improve this project.

---

## 📜 License

This project is open-source under the MIT License.

---

## 👨‍💻 Author

**Rajesh Kannan B**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
