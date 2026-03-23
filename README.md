# Resume Screening and Analysis

This project is a simple implementation of a resume screening system using basic NLP techniques. It takes resume text data and compares it with a given job description to rank candidates based on relevance.

## What this project does

- Cleans and preprocesses resume text
- Converts text into numerical form using TF-IDF
- Compares resumes with a job description
- Ranks candidates using cosine similarity

## Tech used

- Python
- Pandas
- Scikit-learn

## How it works

1. Load the resume dataset
2. Clean the text (remove symbols, lowercase, etc.)
3. Apply TF-IDF to convert text into vectors
4. Compare resumes with job description
5. Generate similarity scores and rank candidates

## Project structure

```
resume-screening-and-analysis/
│
├── data/
│   └── resumes.csv
│
├── notebooks/
│   └── resume_analysis.ipynb
│
└── README.md
```

## Note

This is a basic project created for learning and understanding how NLP can be used in resume screening.
