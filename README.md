# AI-powered-Resume-Screening-and-Ranking-System

This project is an AI-powered resume screening and ranking system that uses machine learning to evaluate and rank resumes based on their relevance to a given job description. The system extracts text from uploaded resume PDFs, computes the similarity between each resume and the job description, and ranks the resumes accordingly. The system uses the TF-IDF vectorizer and cosine similarity to perform the ranking.

## Features

- **PDF Resume Upload:** Upload multiple resume PDFs.
- **Job Description Input:** Provide a job description to evaluate the resumes against.
- **Resume Ranking:** Rank resumes based on their similarity to the provided job description.
- **CSV Download:** Export the ranking results as a CSV file for further analysis.
  
## Technologies

- **Python**  
- **Streamlit** - For creating the web application.
- **PyPDF2** - For extracting text from PDF resumes.
- **Scikit-learn** - For text processing using TF-IDF and cosine similarity.
- **NLTK** - For natural language processing (removing stopwords).

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone (https://github.com/soundarapandi-art/AI-powered-Resume-Screening-and-Ranking-System)
   cd AI-Resume-Screening
