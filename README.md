# Resume Screening & Candidate Ranking System

## Overview

This project automates the resume screening process using Machine Learning and Natural Language Processing (NLP). The system compares candidate resumes with a given job description and ranks candidates based on their relevance to the job requirements.

The objective is to help recruiters quickly identify the most suitable candidates and reduce the time spent manually reviewing resumes.

---

## Features

* Resume text preprocessing
* Job description matching
* TF-IDF based feature extraction
* Resume-to-job similarity scoring
* Candidate ranking based on match scores
* Visualization of candidate rankings
* Easy to extend for recruitment and HR applications

---

## Dataset

The project uses a resume dataset containing candidate resume text from various job domains.

Each record includes:

* Resume Text
* Job Category

Example Categories:

* Data Science
* Python Developer
* Java Developer
* HR
* Web Designing
* Testing
* DevOps Engineer
* Business Analyst
* Network Security Engineer

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP)
* Matplotlib
* Jupyter Notebook

---

## Workflow

1. Load the resume dataset.
2. Define a job description.
3. Preprocess resume text.
4. Convert resumes and job description into numerical features using TF-IDF Vectorization.
5. Calculate similarity scores using Cosine Similarity.
6. Rank candidates based on their match score.
7. Visualize candidate rankings using a bar chart.
8. Identify the most suitable candidates for the job role.

---

## Machine Learning & NLP Techniques

### Feature Extraction

* TF-IDF (Term Frequency-Inverse Document Frequency)

### Similarity Measurement

* Cosine Similarity

### Why NLP?

* Converts unstructured resume text into machine-readable format.
* Extracts important keywords and skills.
* Enables intelligent comparison between resumes and job descriptions.

---

## Applications

* HR Recruitment Automation
* Resume Screening
* Candidate Shortlisting
* Talent Acquisition
* Applicant Tracking Systems (ATS)
* Resume Ranking Systems

---

## Results

The system successfully:

* Compares resumes against a job description
* Calculates candidate match scores
* Ranks candidates according to job relevance
* Generates visual ranking reports

### Output

* Resume Match Scores
* Ranked Candidate List
* Candidate Ranking Graph

---

## Project Structure

FUTURE_ML_03/

├── data/
│   └── resume_dataset.csv

├── images/
│   └── resume_ranking.png

├── notebooks/
│   └── resume_screening.ipynb

├── requirements.txt

└── README.md

---

## Future Enhancements

* Skill Gap Analysis
* Resume Parsing
* Keyword Extraction
* Weighted Skill Matching
* Job Recommendation System
* Deep Learning Models (BERT)
* Web Deployment using Streamlit or Flask

---

## Author

**RithvikRaj Karakambadi**
