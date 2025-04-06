# 🎯 Placement Portal with Job Recommendation

A smart placement portal that recommends jobs based on a user's profile using machine learning. Designed to simplify the job-hunting process for students and freshers by providing intelligent suggestions based on skills, experience, and interests.

---

## 🚀 Features

- 🔍 **Job Recommendation Engine** using NLP and machine learning
- 👨‍🎓 **Student/Job Seeker Profile Management**
- 🗃️ **Admin Panel** for adding new job listings
- 📊 **Skill Matching Algorithm** for personalized results
- 📄 Clean and simple user interface (Django-based)
- 📈 Resume parsing & keyword analysis (optional)
- 📥 CSV upload support for job data

---

## 🛠️ Tech Stack

- **Backend**: Python, Django
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (can be switched to PostgreSQL)
- **Version Control**: Git & GitHub

---

## 💡 How It Works

1. User signs up and enters details (skills, experience, interests).
2. Admin uploads available jobs with required skillsets.
3. ML model compares the user's profile to job listings.
4. Job recommendations are shown based on similarity scores.

---

## 🧠 Machine Learning Model

- Text preprocessing: Tokenization, Stopword removal
- Feature extraction: TF-IDF / CountVectorizer
- Classification / Matching using cosine similarity or logistic regression
- Training dataset: Manually labeled job descriptions and profiles


---

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/job-recommendation-portal.git
cd job-recommendation-portal

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows


# Run the project
python manage.py runserver
