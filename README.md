# 📌 Student Registration System (Django):

A simple and clean Django-based Student/Candidate Registration System that allows users to register their details, upload profile images and documents, and view candidate details.


# 🚀 Features:

✅ Student Registration Form (ModelForm)

✅ Gender Selection (Radio Button)

✅ Preferred Job Cities (Multiple Checkbox Selection)

✅ Indian States Dropdown

✅ 6-digit Pincode Validation

✅ 10-digit Mobile Number Validation (Regex)

✅ Profile Image Upload

✅ Document Upload (PDF, DOCX, etc.)

✅ Candidate Detail Page

✅ Clean Bootstrap UI

# 🛠️ Tech Stack:

Backend: Django

Frontend: HTML, Bootstrap,javascript

Database: SQLite (Default Django DB)


# 📂 Project Structure:
student/
│
├── models.py
├── forms.py
├── views.py
├── urls.py
├── templates/
│   └── student/
│       ├── home.html
│       └── candidate.html



# 🧠 Model Overview:
Profile Model Fields:

- name

- dob

- gender

- locality

- city

- pin (6-digit validation)

- state (Dropdown choices)

- mobile (Regex validated – 10 digits)

- email

- job_city

- profile_image

- my_file

# 🔍 Validation Implemented:
📌 Pincode Validation

Must be exactly 6 digits.

📌 Mobile Number Validation

Must be exactly 10 digits.

Only numeric values allowed.

Implemented using Django RegexValidator.


# 🌆 Job Cities Included:

- Bengaluru

- Mumbai

- Hyderabad

- Pune

- Chennai

- Delhi

- Noida

- Gurugram

- Ahmedabad

- Kolkata

- ETC


# 📦 Installation & Setup:
# 1️⃣ Clone the repository
      git clone https://github.com/your-username/your-repo-name.git
      cd your-repo-name
# 2️⃣ Create Virtual Environment
     python -m venv env
     env\Scripts\activate   # Windows
# 3️⃣ Install Dependencies
     pip install django
# 4️⃣ Run Migrations
    python manage.py makemigrations
    python manage.py migrate
# 5️⃣ Run Server
     python manage.py runserver

# Visit:

      http://127.0.0.1:8000/
    

# 📌 Future Improvements:

🔹 Store Multiple Job Cities properly using ManyToManyField

🔹 Add Login & Authentication

🔹 Add Pagination

🔹 Add Search & Filter Feature

🔹 Deploy on PythonAnywhere / Render

# 👨‍💻 Author:

Vipin Yadav
Aspiring Software Engineer 🚀:
Open to opportunities 💼 

# 📄 License

This project is open-source and free to use.
