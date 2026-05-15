# SmartHire

![GitHub repo size](https://img.shields.io/github/repo-size/mdayantech/smart-hire)
![GitHub license](https://img.shields.io/github/license/mdayantech/smart-hire)

## Overview
SmartHire is an AI‑powered recruitment platform that automates job posting, candidate matching, and skill extraction. It showcases full‑stack development with a Python backend, HTML templates, and natural‑language processing for resume analysis.

## Who Is This For?
- **HR Professionals** looking for an intuitive tool to post jobs and quickly discover qualified candidates.
- **Recruiters** who need automated skill extraction and ranking.
- **Developers** interested in an end‑to‑end example of AI‑driven hiring pipelines.

## Key Features
- **Job Posting** – Simple web form to create and publish job listings.
- **Resume Parsing** – Extracts keywords, skills, and experience using NLP.
- **Candidate Matching** – Scores candidates against job requirements.
- **Responsive UI** – Clean HTML templates for a pleasant user experience.

## Tech Stack
- **Backend:** Python 3.11, Flask (or FastAPI if applicable), `pandas`, `scikit‑learn`
- **Frontend:** HTML5, CSS3 (modern styling), Jinja2 templates
- **AI/NLP:** `spaCy`, `nltk` for keyword extraction
- **Database:** SQLite (lightweight for demo) – can be swapped for PostgreSQL
- **Version Control:** Git, hosted on GitHub

## Getting Started
1. **Clone the repo**
   ```bash
   git clone https://github.com/mdayantech/smart-hire.git
   cd smart-hire
   ```
2. **Create a virtual environment**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate   # Windows
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the application**
   ```bash
   python app.py   # or flask run if using Flask
   ```
   Open a browser at `http://127.0.0.1:5000`.

## How HR Uses It
- **Add a Job** – Navigate to the *Add Job* page, fill in title, description, and required skills.
- **View Candidates** – After candidates upload resumes, the system extracts keywords and ranks them based on relevance.
- **Export Results** – Export candidate lists as CSV for further reviewing.

## Contributing
Feel free to submit pull requests, open issues, or suggest new features. Follow the standard GitHub workflow:
1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

## License
This project is licensed under the MIT License – see the `LICENSE` file for details.

