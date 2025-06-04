# 📝 Resume Parser using NLP and Python

This project is a smart resume parsing tool that extracts structured data from unstructured PDF resumes. It uses Natural Language Processing (NLP) and pattern recognition to identify key fields such as name, email, phone, skills, and social profiles.

---

## 🧠 Objective

Automate the process of extracting candidate information from resumes to support ATS (Applicant Tracking System) pipelines and HR workflows.

---

## 📊 Features

- ✅ Extracts **Name**, **Email**, **Phone Number**
- ✅ Identifies **Skills** using keyword matching
- ✅ Pulls **LinkedIn / GitHub links**
- ✅ Outputs result as structured **JSON**
- ✅ Ready for integration into apps or dashboards

---

## 🛠️ Technologies Used

- **Python**
- **PyMuPDF** (for PDF parsing)
- **spaCy** (for Named Entity Recognition)
- **Regular Expressions (Regex)**

---

## 📁 Project Structure

resume-parser/
├── sample_resumes/
│   └── Kanish_Resume_DS.pdf
├── parser/
│   └── extractor.py
├── output/
│   └── kanish_resume_parsed.json
├── requirements.txt
└── README.md

---

## ⚙️ How to Run

### 📌 1. Install dependencies:
```bash
pip install pymupdf spacy
python -m spacy download en_core_web_sm
python parser/extractor.py
output/kanish_resume_parsed.json
```
## 📤 Sample Output
json
{
  "name": "Kanish Tyagi",
  "email": "kanishtyagi123@gmail.com",
  "phone": "+1 (682) 217 0329",
  "links": [
    "https://linkedin.com/in/kanishtyagi123",
    "https://github.com/kanish5"
  ],
  "skills": ["Python", "SQL", "Pandas", "Power BI", "Scikit-learn", "Excel"]
}

---

## Future Enhancements
	•	Add PDF drag-and-drop UI using Streamlit
	•	Extract education, experience, and certifications
	•	Train a custom NLP model using labelled resumes

 ---

 ## Autor

👤 Kanish Tyagi
📫 kanishtyagi123@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/kanishtyagi123) | [GitHub](https://github.com/kanish5)
