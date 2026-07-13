# 🤖 AI Resume Analyzer

> An AI-powered Resume Analyzer that extracts resume information, evaluates candidate profiles, predicts suitable job roles, and provides personalized recommendations using Natural Language Processing (NLP).

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

AI Resume Analyzer is a web-based application that helps users analyze resumes by extracting key information such as skills, education, experience, and keywords. The application leverages Natural Language Processing (NLP) techniques to provide intelligent insights, recommend improvements, predict suitable job roles, and generate resume analytics.

This project is designed to simplify resume screening for both job seekers and recruiters.

---

## ✨ Features

### 👤 User Features

- Upload resumes in PDF format
- Extract resume details automatically
- Identify technical skills and keywords
- Predict suitable job roles
- Recommend additional skills
- Suggest certifications and learning resources
- Resume scoring based on content
- Resume improvement suggestions
- Resume analytics and insights
- Interview preparation resources

### 👨‍💼 Admin Features

- Dashboard for managing applicants
- View uploaded resumes
- Export applicant data to CSV
- User analytics
- Resume score statistics
- Skill distribution
- Experience analysis
- Feedback management

---

## 🛠 Tech Stack

### Frontend

- Streamlit
- HTML
- CSS
- JavaScript

### Backend

- Python

### Database

- MySQL

### Libraries

- Streamlit
- Pandas
- NLTK
- Plotly
- pdfminer3
- pyresparser
- spaCy

---

## ⚙️ How It Works

1. User uploads a resume.
2. Resume text is extracted.
3. NLP processes the extracted content.
4. Skills, education, projects, and experience are identified.
5. Resume score is calculated.
6. Suitable job roles are predicted.
7. Personalized recommendations are displayed.

---

## 📂 Project Structure

```
AI-Resume-Analyzer/
│
├── App/
├── Uploaded_Resumes/
├── pyresparser/
├── requirements.txt
├── App.py
└── README.md
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/<your-username>/AI-Resume-Analyzer.git
```

### Create Virtual Environment

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Download spaCy Model

```bash
python -m spacy download en_core_web_sm
```

### Configure Database

Create a MySQL database:

```
cv
```

Update the database credentials in:

```
App.py
```

### Run the Application

```bash
streamlit run App.py
```

---

## 📸 Screenshots

> Add screenshots of your application here.

- Home Page
- Resume Upload
- Resume Analysis
- Skill Recommendation
- Dashboard
- Analytics

---

## 💡 Future Enhancements

- Resume comparison
- ATS compatibility checker
- AI-powered resume rewriting
- LinkedIn profile analysis
- Multi-language resume support
- Authentication & authorization
- Cloud deployment
- REST API support

---

## 📈 Learning Outcomes

Through this project, I gained experience with:

- Natural Language Processing (NLP)
- Resume Parsing
- Streamlit Web Development
- Python Backend Development
- MySQL Integration
- Data Visualization
- PDF Text Extraction
- Recommendation Systems

---

## 🤝 Contributing

Contributions are welcome.

If you would like to improve this project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📬 Contact

**Mahesh**

- GitHub: https://github.com/<your-username>
- LinkedIn: https://linkedin.com/in/<your-linkedin>
- Email: your-email@example.com

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.
