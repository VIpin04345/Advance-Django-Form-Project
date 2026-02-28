# 📌 Student Registration System (Django)

A simple and clean Django-based Student/Candidate Registration System that allows users to register their details, upload profile images and documents, and view candidate details.


# 🚀 Features

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

# 🛠️ Tech Stack

Backend: Django

Frontend: HTML, Bootstrap,javascript

Database: SQLite (Default Django DB)


# 📂 Project Structure
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


# 🧠 Model Overview
Profile Model Fields:

name

dob

gender

locality

city

pin (6-digit validation)

state (Dropdown choices)

mobile (Regex validated – 10 digits)

email

job_city

profile_image

my_file

# 🔍 Validation Implemented
📌 Pincode Validation

Must be exactly 6 digits.

📌 Mobile Number Validation

Must be exactly 10 digits.

Only numeric values allowed.

Implemented using Django RegexValidator.
