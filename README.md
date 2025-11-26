# AI Resume Analyzer

> A tool that parses resume content using Natural Language Processing (NLP), extracts and clusters keywords into sectors, and provides recommendations, predictions, and analytics for applicants and recruiters.

---

## 🚀 Overview

This project extracts structured information from resumes (PDF / DOCX), converts unstructured text into tabular form (CSV), and provides recommendations and analytics based on keyword matching. It is useful for applicants improving their resumes, recruiters screening candidates, and colleges analysing placement readiness.

### Main capabilities
- Parse resumes to extract: basic info, skills, keywords, education, experience, etc.
- Cluster keywords into industry/role sectors.
- Provide recommendations: skills to add, suggested courses/certificates, resume tips, predicted roles.
- Produce analytics dashboards and CSV exports for organizational use.

---

## 📌 Scope

1. Convert resume data into a structured format (CSV / tabular) for analytics.
2. Give recommendations, predictions, and an overall resume score for iterative improvement.
3. Drive traffic through a user section (applicant testing & feedback).
4. Enable colleges to get insights into student resumes before placements.
5. Generate analytics for popular roles among users.
6. Improve models & UX using feedback.

---

## 🧰 Tech Stack

- **Frontend:** (Streamlit / your chosen frontend)
- **Backend:** Python (NLP & parsing logic)
- **Database:** MySQL
- **Packages:** spaCy, pyresparser (custom replacement), and other dependencies listed in `requirements.txt`

---

## ✅ Features

### Applicant (Client)
- Resume parsing for: Basic Info, Skills, Keywords
- Location & misc. data fetching
- Recommendations:
  - Skills to add
  - Predicted job role
  - Suggested courses & certificates
  - Resume tips & ideas
  - Overall score
  - Interview & resume tip videos

### Admin
- Export all applicants to CSV
- View uploaded resumes folder
- View & aggregate user feedback and ratings
- Charts & analytics:
  - Ratings (pie chart)
  - Predicted roles (pie chart)
  - Experience level distribution
  - Resume score distribution
  - User counts by city/state/country
  - Feedback and comments history

---

## 🔧 Requirements

Install these before running the project:

- Python `3.9.12` (recommended) — https://www.python.org/
- MySQL — https://www.mysql.com/
- Visual Studio Code (recommended) — https://code.visualstudio.com/
- Visual Studio Build Tools for C++ (Windows only) — https://aka.ms/vs/17/release/vs_BuildTools.exe

> Note: The project works with other Python 3.9.x versions in most cases, but any major differences are not guaranteed.

---

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/deepakpadhi986/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
