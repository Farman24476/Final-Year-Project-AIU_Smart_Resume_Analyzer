# AIU Smart Resume Analyzer

**Live Project:** [aiu-smart-resume-analyzer.up.railway.app](https://aiu-smart-resume-analyzer.up.railway.app/)

The AIU Smart Resume Analyzer is a next-generation web-based application designed to modernize and streamline the résumé screening process using Artificial Intelligence (AI) and Natural Language Processing (NLP). This project addresses the inefficiencies, biases, and inconsistencies inherent in traditional hiring workflows, especially within academic and entry-level recruitment contexts.

By combining advanced NLP techniques with secure authentication and an Applicant Tracking System (ATS) scoring engine, the system enables accurate résumé parsing, job-candidate matching, and skill-gap identification. A role-based, user-friendly dashboard provides actionable insights to both administrators and applicants. Experimental results demonstrate that the platform significantly improves decision-making, enhances fairness, and reduces manual review time.

---

## Key Features

- **Intelligent Resume Parsing**  
  Automatically extracts structured data (education, skills, experience) from PDF and DOCX formats using spaCy.

- **ATS Scoring Engine**  
  Calculates match scores between candidate profiles and job descriptions using NLP-based similarity metrics.

- **Secure Authentication**  
  Implements JWT-based authentication with Firebase Auth and bcrypt encryption.

- **Skill-Gap Analysis & Keyword Matching**  
  Identifies missing or mismatched skills, helping both recruiters and applicants.

- **Administrative Dashboard**  
  Interactive web dashboard for visualizing analytics, tracking applicant performance, and managing user roles.

- **Backend-Frontend Integration**  
  Built with FastAPI for backend logic and Firebase for real-time data storage and authentication. Optional React.js frontend available.

---

## Technology Stack

**Frontend**  
- HTML, CSS, JavaScript  
- Optional React.js for dynamic UI rendering

**Backend**  
- Python (FastAPI framework)

**Database & Authentication**  
- Firebase Firestore (NoSQL database)  
- Firebase Authentication with JWT

**NLP & Parsing Libraries**  
- spaCy for entity recognition and linguistic analysis  
- PDFMiner for PDF text extraction  
- pandas for data manipulation

**Security**  
- JWT for secure token-based sessions  
- bcrypt for password hashing

**Data Visualization**  
- matplotlib and Chart.js for charting analytics

---

## Testing & Validation

- **Unit Testing:** Backend endpoints, résumé parsing, and scoring modules tested independently  
- **Integration Testing:** Full workflow validation from upload to dashboard scoring  
- **User Acceptance Testing (UAT):** Feedback collected from academic staff and HR interns  
- **Benchmarking:** Compared system-generated scores with manual HR review for accuracy and fairness

---

## Future Development Roadmap

| Feature                    | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| PDF Report Generator       | Export detailed résumé analysis reports as downloadable PDFs                |
| OTP-Based Login            | Add One-Time Password (OTP) authentication for enhanced login security      |
| GPT/LLM Integration        | Use large language models to refine feedback and profile interpretation     |
| Super Admin Panel          | Create a system-wide management console with advanced controls              |
| Career Guidance Tools      | Recommend relevant courses, trainings, and job-prep resources to users      |
| AIU Portal Integration     | Seamless integration with the AIU Student Information and Career Portal     |

---

## Impact

The AIU Smart Resume Analyzer offers a scalable, secure, and intelligent alternative to manual résumé screening. By reducing hiring bottlenecks and promoting equitable assessment practices, the system contributes to more inclusive and data-driven recruitment in educational and professional environments. Its modular architecture and open-stack technology make it easily extensible to broader HR systems or academic platforms.

---

## Acknowledgments

This project was developed as part of the 2025 Final Year Capstone at Albukhary International University (AIU), under the supervision of academic faculty from the School of Computing and Informatics.

**Project Team**  
- Md Farman Ali (Team Leader) 
- Tawfiq Taib Yassen  
- Abdelrahman M. K. Abualhana  

© 2025 AIU Final Year Project Team
  Please do not copy anything.
