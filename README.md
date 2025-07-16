# 🧠 Online Course Platform – Final Project

This Django-based web application allows learners to enroll in courses, take exams, and view their results. It was extended as part of a final project to include assessment and grading functionality.

---

## 🚀 Features Implemented

- Admin interface for managing:
  - Courses and Lessons
  - Questions and Choices (multiple-selection)
- Exam functionality:
  - Learners can take exams after enrolling
  - Exams allow selecting multiple answers per question
  - Automatic grading based on correct answers
  - Pass/fail feedback with detailed explanations
- Retake option if failed
- Responsive frontend using Bootstrap 4

---

## 🧩 Technologies Used

- Django (Python)
- SQLite (default DB)
- Bootstrap 4
- HTML templates
- Admin panel integration

---

## 📁 Key Files and Structure

```bash
onlinecourse/
├── models.py                # Models: Course, Lesson, Question, Choice, Submission
├── views.py                 # Logic: submit exam, evaluate results
├── templates/
│   ├── course_detail_bootstrap.html
│   └── exam_result_bootstrap.html
├── admin.py                 # Admin site configuration


## ⚙️ Setup and Run Instructions

Follow these steps to set up the project locally and start the development server:

1. **Run database migrations:**

```bash
python manage.py makemigrations
python manage.py migrate

2. **Create a superuser to access the admin site:**
python manage.py createsuperuser

3. **Start the Django development server:**
python manage.py runserver

4. **Access the admin panel:**

Open your browser and go to:  
`http://127.0.0.1:8000/admin/`

Log in using the superuser credentials you created earlier.


