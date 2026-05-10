# Detection_of_Cyberbullying 🚨

A machine learning-based web application developed using Python, Django, Natural Language Processing (NLP), and MySQL (XAMPP) to detect cyberbullying content on social media platforms.

The system analyzes text input and classifies whether it contains cyberbullying or non-cyberbullying content using trained machine learning models.

---

## 📌 Features

- Detects cyberbullying text in real time
- Machine Learning-based text classification
- NLP text preprocessing
- User-friendly web interface using Django
- MySQL database integration (XAMPP)
- Stores prediction results in database
- Supports multiple ML models for comparison

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Django

### Machine Learning & NLP
- Scikit-learn
- Pandas
- NumPy
- NLTK
- TF-IDF Vectorization

### Database
- MySQL (XAMPP / phpMyAdmin)

---

## 🤖 Machine Learning Algorithms Used

- Support Vector Machine (SVM)
- Naive Bayes
- Logistic Regression

These algorithms are compared to identify the best-performing classifier for cyberbullying detection.

---

## 📂 Project Structure

```bash
Detection_of_Cyberbullying/
│── Database/
│── detection_of_cyberbullying/
│── Tweet_DataSets.xlsx
│── DataStructure.txt
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation

Clone repository:

```bash
git clone https://github.com/Anjali-36/Anjali-36-Detection-Of-CyberBullying-On-Social-Media-Using-Machine-Learning.git
```


Create virtual environment:

```bash
python -m venv venv
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```
---

### 🗄️ Database Setup (XAMPP - MySQL)
1. Start XAMPP
Open XAMPP Control Panel and start:
- Apache
- MySQL

2. Create Database

Go to:
http://localhost/phpmyadmin

Create database:
cyberbullying_db


3. Configure Django Database

Update settings.py:
```python

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'cyberbullying_db',
        'USER': 'root',
        'PASSWORD': '',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

4. Run Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

---

Run project:

```bash
python manage.py runserver
```

Open browser:

```bash
http://127.0.0.1:8000/
```

---

## 🎯 Objective

The main objective of this project is to detect harmful online behavior by automatically identifying cyberbullying text using machine learning and NLP techniques.

This helps create safer online communication environments.

---

## 📊 Dataset

The project uses labeled text/tweet datasets containing:

- Cyberbullying text
- Non-cyberbullying text

Preprocessing includes:

- Tokenization
- Stopword removal
- Text normalization
- TF-IDF feature extraction

---

## 📈 Model Workflow

- Text input from user
- Preprocessing using NLP
- Feature extraction using TF-IDF
- ML model prediction
- Result displayed on UI
- Stored in MySQL database

## 👩‍💻 Author

**Anjali**  
Computer Science Graduate | Python Developer | Machine Learning Enthusiast

---

## ⭐ Support

If you found this project useful, consider giving it a **star ⭐**
