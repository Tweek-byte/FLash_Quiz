# Flash Quiz

A smart and structured AI-powered evaluation system designed for students and professors. This platform automates quiz generation, enhances academic integrity with anti-cheating mechanisms, and provides real-time notifications and detailed result tracking.

---

## 🚀 Quick Start for Collaborators

### Clone the Repository

```sh
# Open your terminal or command prompt and run:
git clone https://github.com/your-repo/flash_quiz.git
cd flash_quiz
```

### Set Up Virtual Environment

```sh
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### Install Dependencies

```sh
pip install -r requirements.txt
```

### Run Migrations

```sh
python manage.py migrate
```

### Start Development Server

```sh
python manage.py runserver
```

Access the app at: `http://127.0.0.1:8000/`

---

## ✨ Features & Workflow

### 1️⃣ Authentication & User Roles

- **Signup Flow:**
  - **Professor:** Registers with name, email, password, and department.
  - **Student:** Registers with name, email, password, major, and semester.
  - System assigns respective permissions.
- **Login & Password Reset:** Secure login with a "Forgot Password?" option.

### 2️⃣ Dashboard

#### **Student Dashboard**

- View available and past evaluations.
- Manage profile details.
- Track quiz history and results.

#### **Professor Dashboard**

- View created quizzes and student performance.
- Create new quizzes from uploaded materials.
- Manage personal profile details.

### 3️⃣ AI-Powered Quiz Creation

- Upload course material (PDF, DOCX, or plain text).
- AI processes content and generates quiz questions.
- Customize quiz (edit questions, set time limits, assign to students).

### 4️⃣ Student Quiz-Taking Experience

- Students can take active quizzes within the set time.
- Automatic submission before the timer expires.

### 5️⃣ Anti-Cheating Mechanism

- Tab switching is logged and notified to professors.
- Optionally warns students for suspicious behavior.

### 6️⃣ Evaluation & Reporting

- **Students:** Can only view their own scores.
- **Professors:** Get insights into student performances.

---

## 🛠 Tech Stack

- **Backend:** Django (Python), Django REST Framework, Celery + Redis
- **Frontend:** HTML, CSS, JavaScript (React.js or Django Templates)
- **Database:** PostgreSQL
- **AI Component:** Deepseek AI for quiz generation
- **Deployment:** Replit

---

## 📌 Summary

This AI-driven quiz platform automates evaluation, enhances security, and streamlines academic assessments. With dedicated dashboards for professors and students, structured workflow, and anti-cheating features, Flash Quiz ensures a seamless and fair assessment process.\
\
Best Regards, Zakaria Aabab.

