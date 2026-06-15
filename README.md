 # ❤️ MedBuddy.ML - Heart Disease Prediction System

An AI-powered healthcare application that predicts the likelihood of heart disease using Machine Learning. The system allows users to enter patient health parameters and instantly receive a prediction along with a probability score.

---

## 🚀 Project Overview

Heart disease is one of the leading causes of death worldwide. MedBuddy.ML leverages Machine Learning to analyze patient health metrics and predict the risk of heart disease, enabling early awareness and decision-making.

---

## ✨ Features

- Heart Disease Risk Prediction
- Probability Score Generation
- User-Friendly Web Interface
- Real-Time Prediction
- Data-Driven Healthcare Insights
- Responsive Input Form

---

## 🏗️ Application Architecture

![Application Architecture](screenshots/architecture.png)

### Workflow

1. User enters patient details.
2. Flask backend receives the input.
3. Data is preprocessed and validated.
4. Trained Machine Learning model performs prediction.
5. Probability score is calculated.
6. Result is displayed on the web interface.

---

## 📸 Screenshots

### Patient Details Form

![Patient Form](screenshots/prediction-form.png)

### Prediction Result

![Prediction Result](screenshots/result-page.png)

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- Bootstrap

### Backend
- Python
- Flask

### Machine Learning
- Scikit-Learn
- Pandas
- NumPy

### Deployment
- Flask Server
- AWS EC2 (if deployed)

---

## 📊 Machine Learning Pipeline

```text
Data Collection
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Serialization (.pkl)
      ↓
Flask Integration
      ↓
Prediction Interface
```

## 📂 Project Structure

```text
MedBuddy.ML/
│
├── app.py
├── requirements.txt
├── model/
│   └── heart_disease_model.pkl
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   └── images/
│
├── screenshots/
│   ├── architecture.png
│   ├── prediction-form.png
│   └── result-page.png
│
└── README.md
```

## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/MedBuddy.ML.git
cd MedBuddy.ML
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

Open:

```text
http://localhost:5000
```

---

## 📈 Model Output

The model provides:

- Heart Disease Prediction
- Risk Probability Score
- Instant Results

Example:

```text
Heart Disease Probability: 0.77
Prediction: Heart Disease Detected
```

---

## 🔮 Future Enhancements

- Explainable AI (SHAP/LIME)
- PDF Medical Report Generation
- Doctor Recommendation System
- Cloud Deployment with AWS
- User Authentication
- Patient History Tracking

---

## 🎯 Learning Outcomes

- Machine Learning Model Development
- Data Preprocessing Techniques
- Flask Web Development
- Model Deployment
- End-to-End ML Project Implementation

---

## 👨‍💻 Author

**Manasvi Pusam**

LinkedIn: Your LinkedIn URL

GitHub: Your GitHub URL

---

⭐ If you found this project useful, consider giving it a star!
