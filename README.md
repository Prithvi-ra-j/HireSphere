# HireSphere: AI-Powered Recruitment Assistant

## Overview
HireSphere is an AI-powered recruitment assistant designed to streamline the recruitment process. It utilizes cutting-edge technologies such as SQLite, pandas, HuggingFace Transformers, and PyMuPDF to parse job descriptions and resumes, evaluate candidate-job fit, and provide insights to improve the hiring process. The platform is capable of matching candidates to job openings based on skills, experience, and other criteria.

## Features
- **Job Parsing**: Extracts and organizes job descriptions for easy evaluation.
- **Resume Parsing**: Extracts and structures candidate data from resumes.
- **Candidate-Job Matching**: Matches candidates to jobs based on a scoring system.
- **Shortlisting**: Marks candidates who meet job criteria as shortlisted.
- **Automatic Email**: Sends interview invitations to shortlisted candidates.
- **Database Management**: Uses SQLite for storing job listings, candidates, and match data.

## Tech Stack
- **Backend**: Python
- **Database**: SQLite
- **AI/ML**: HuggingFace Transformers (for NLP-based job and resume parsing)
- **PDF Parsing**: PyMuPDF (for extracting data from resumes in PDF format)
- **Libraries**: pandas, sqlite3

## Progress
### Completed Features:
- **CV Agent**: Parses and extracts data from candidate resumes.
- **JD Agent**: Parses and structures job descriptions to extract relevant details.
- **Matching Agent**: Compares candidate data with job descriptions and calculates match scores.

### Work in Progress:
- **Controller**: The controller will handle the orchestration of the overall workflow between job and candidate data, facilitating the job parsing, candidate matching, and shortlisting processes.
- **Interview Scheduling & Email Invitations**: The interview scheduling system will send automatic interview invitations to shortlisted candidates.


## Usage

### Job Matching
- **Step 1**: Add job listings via the `jobs` table.
- **Step 2**: Add candidates via the `candidates` table.
- **Step 3**: Use the `match_jobs` function to match candidates to job descriptions.
- **Step 4**: Review match scores and shortlist suitable candidates.
- **Step 5**: Send interview invitations to shortlisted candidates.


