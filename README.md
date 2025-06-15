# 🧠 Automated Resume Grader

A smart  web application built using *Streamlit* that analyzes and scores uploaded resumes, suggests relevant job roles, and recommends personalized learning resources to enhance candidate profiles.

---

## 🚀 Features

✅ Upload and analyze PDF resumes  
✅ Score resume based on skills, structure, and relevance  
✅ Recommend personalized career learning paths  
✅ Suggest job titles based on resume content  
✅ Streamlit-based interactive UI  

---

🛠 Tech Stack

Python 3.13.5

Streamlit – For building the UI

pyresparser – Resume parsing

spaCy & NLTK – For text extraction and entity recognition

pandas, Pillow, pymysql – Data handling and backend integration

streamlit-tags, pafy – For enhanced UI inputs and video integration

---

🧪 How It Works

1. User uploads a pdf or txt format resume.

2. The system extracts key information using NLP:
Name, Contact Details, Degree, University, Experience, Skills

3. Resume is analyzed to:
Generate a score out of 100
Suggest matching job titles like:

Software Developer
Data Scientist
Android Developer
iOS Developer
UI/UX Designer
Full Stack Developer
Machine Learning Engineer



## 📥 Installation

### 🔗 Clone the Repository

```bash
git clone https://github.com/your-username/Automated_Resume_Grader.git
cd Automated_Resume_Grader

🧱 Create Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

📦 Install Dependencies

pip install -r requirements.txt

---

▶ Run the App

streamlit run app.py

App will launch in your browser at http://localhost:8501


---
