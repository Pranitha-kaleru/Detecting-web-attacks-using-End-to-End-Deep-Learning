# 🛡️ Detecting Web Attacks Using End-to-End Deep Learning

A deep learning-based cybersecurity application that detects and classifies web attacks using neural networks. The system leverages machine learning and deep learning models to improve the detection of malicious web requests and enhance web application security.

---

## 📌 Features

- User Registration with OTP Verification
- Secure User Login
- Dataset Upload
- Data Preprocessing
- Existing Algorithm Comparison
  - Support Vector Machine (SVM)
  - Naïve Bayes
- Proposed Autoencoder Model
- Extension using LSTM Deep Learning
- Performance Evaluation
- Accuracy Comparison Graphs
- Interactive Django Web Interface

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Framework
- Django 2.1.7

### Database
- SQLite / MySQL

### Libraries
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- PyMySQL

---

## 📂 Project Structure

```
Detecting-web-attacks-using-End-to-End-Deep-Learning/
│
├── Dataset/
├── Web/
├── WebApp/
├── manage.py
├── requirements.txt
├── run.bat
├── DB.txt
├── README.md
├── SCREENS.docx
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Pranitha-kaleru/Detecting-web-attacks-using-End-to-End-Deep-Learning.git
```

### Navigate to the project

```bash
cd Detecting-web-attacks-using-End-to-End-Deep-Learning
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the environment

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure Database

Import the SQL script from **DB.txt** into your database or configure SQLite/MySQL according to your environment.

### Run the project

```bash
python manage.py runserver
```

Open your browser:

```
http://127.0.0.1:8000/
```

---

## 📊 Machine Learning Models

- Support Vector Machine (SVM)
- Naïve Bayes
- Autoencoder
- Long Short-Term Memory (LSTM)

---

## 📈 Performance

The project compares traditional machine learning algorithms with deep learning models using metrics such as:

- Accuracy
- Precision
- Recall
- F1 Score

LSTM demonstrates improved recall and overall performance for detecting web attacks.

---

## 📷 Screenshots

Project screenshots are available in **SCREENS.docx**.

---

## 🚀 Future Improvements

- Real-time traffic monitoring
- REST API integration
- Docker deployment
- Cloud deployment (AWS/Azure)
- Explainable AI (XAI)
- Transformer-based models
- Live attack dashboard

---

## 👩‍💻 Author

**Pranitha Kaleru**

- GitHub: https://github.com/Pranitha-kaleru
- LinkedIn: https://www.linkedin.com/in/pranitha-kaleru/

---

## 📜 License

This project is developed for educational and research purposes.
