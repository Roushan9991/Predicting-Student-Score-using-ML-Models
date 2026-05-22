# 🎯 Student Performance Predictor | End-to-End ML Pipeline & AWS Deployment

A production-ready Machine Learning application that predicts **student maths scores** using demographic and educational attributes.

This project follows a complete ML lifecycle including:

**Data Ingestion → Data Transformation → Model Training → Model Evaluation → Prediction Pipeline → AWS Deployment**

The application is deployed using **Amazon Elastic Beanstalk**, enabling scalable and cloud-based inference through an interactive web interface.

---

## 🚀 Live Demo

🔗 Application:  
http://mlprojectsp-env.eba-unndhpsn.eu-north-1.elasticbeanstalk.com/

---

## 📌 Project Objective

The objective of this project is to predict student mathematics performance based on various input features such as:

- Gender
- Race / Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

This solution helps demonstrate how machine learning can be used for educational analytics and performance forecasting.

---

# 🏗️ Project Architecture

```text
Raw Data
   ↓
Data Ingestion
   ↓
Data Transformation
   ↓
Feature Engineering
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Best Model Selection
   ↓
Prediction Pipeline
   ↓
Deployment
```

---

## ⚙️ ML Workflow

### 1. Data Ingestion
- Reads dataset
- Splits train/test data
- Stores processed datasets

### 2. Data Transformation
- Handles preprocessing
- Encodes categorical variables
- Standardizes numerical features

### 3. Model Training
Multiple ML algorithms were trained and evaluated:

- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- CatBoost
- AdaBoost

### 4. Model Selection
- Evaluated model performance
- Selected the best-performing model

### 5. Prediction Pipeline
- Accepts user inputs
- Processes features
- Generates score prediction

### 6. Deployment
- Web application deployment
- Interactive prediction interface

---

# 🛠️ Tech Stack

### Programming
- Python

### Machine Learning
- Scikit-learn
- XGBoost
- CatBoost
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Adaboost

### Data Processing
- Pandas
- NumPy

### Deployment
- AWS Elastic Beanstalk

### Backend
- Flask

### Cloud & Deployment
- AWS Elastic Beanstalk
- AWS Environment Hosting

### Development
- Git
- GitHub
---

# 📂 Project Structure

```bash
Predicting-Student-Score-using-ML-Models
│
├── artifacts/
├── notebook/
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   ├── model_trainer.py
│   │
│   ├── pipeline/
│   │   ├── train_pipeline.py
│   │   └── predict_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│
├── templates/
├── app.py
├── requirements.txt
├── setup.py
└── README.md
```

---

# ☁️ Deployment Architecture

```text
User Input
    ↓
Flask Web Application
    ↓
Prediction Pipeline
    ↓
Trained ML Model
    ↓
AWS Elastic Beanstalk
    ↓
Prediction Output
```

# 📈 Key Features

✅ End-to-End ML Pipeline  
✅ Automated Model Training  
✅ Multiple Algorithm Comparison  
✅ Best Model Selection  
✅ Prediction Interface  
✅ Cloud Deployment using AWS Elastic Beanstalk  
✅ Modular Project Structure  

---

# 🖥️ Run Locally

Clone repository:

```bash
git clone https://github.com/Roushan9991/Student-Performance-Predictor-End-to-End-Machine-Learning-Pipeline.git
```

Move into project:

```bash
cd Student-Performance-Predictor-End-to-End-Machine-Learning-Pipeline
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run application:

```bash
python app.py
```

Open:

```text
http://localhost:5000
```

---

# 🚀 Deployment

The application is deployed on **Amazon Web Services (AWS) Elastic Beanstalk** to enable scalable and reliable access.

### Deployment Features:
- Cloud-hosted prediction service
- Environment-based deployment
- Real-time inference
- Web-accessible UI

Live Application:

http://mlprojectsp-env.eba-unndhpsn.eu-north-1.elasticbeanstalk.com/

# 📊 Future Improvements

- Model monitoring
- Feature importance dashboard
- Docker containerization
- CI/CD pipeline
- Experiment tracking (MLflow)
- User authentication
- Batch prediction support

---

## 👨‍💻 Author

**Roushan Kumar Mourya**

MBA (Analytics) | IIM Kashipur  
Mechanical Engineering | NIT Bhopal  

---

⭐ If you found this project useful, consider giving it a star.
