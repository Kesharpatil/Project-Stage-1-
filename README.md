🚨 Intelligent Anomaly Detection System for Digital Transaction Behavior Using ML


A research-driven, hybrid machine learning-based web application designed to detect fraudulent digital transactions using behavioral analysis and anomaly detection techniques.

This system simulates real-time transaction streams and applies a hybrid ML approach to identify suspicious patterns in financial activities.


🚀 Project Overview

Digital payment systems are rapidly growing, increasing the risk of financial fraud. Traditional rule-based systems fail to detect sophisticated and behavioral fraud patterns.

This project implements:

✔ Hybrid Anomaly Detection Model
✔ Behavioral Transaction Analysis
✔ Real-Time Transaction Simulation
✔ Fraud Risk Scoring Dashboard
✔ Django-Based Web Interface


🎯 Key Features

📊 Real-Time Transaction Stream Simulation
🧠 Hybrid ML Model (Isolation Forest + Random Forest)
📈 Fraud Risk Probability Scoring
🔎 Behavioral Pattern Analysis (Device, Location, Amount, Time)
🌐 Django Web Dashboard
📁 Admin Control Panel
📉 Performance Metrics (Precision, Recall, F1-score, ROC-AUC)


🧠 Hybrid Model Architecture

The system combines:

1️⃣ Isolation Forest

Detects unusual transaction patterns

Works well with imbalanced data

2️⃣ Random Forest Classifier

Classifies fraud vs legitimate transactions

Provides fraud probability score

🔁 Hybrid Workflow:

Transaction → Preprocessing → Isolation Forest (Anomaly Score) → Random Forest (Classification) → Final Fraud Risk Output


🛠️ Tech Stack

💻 Frontend: HTML, CSS, JavaScript
🐍 Backend: Django (Python Framework)
📊 Machine Learning: Scikit-Learn
🗃️ Database: SQLite (Upgradeable to PostgreSQL)
📦 Dataset Source: Mendeley Data Repository
📈 Model Evaluation: Precision, Recall, F1-score, ROC-AUC

📊 Dataset Information

Dataset: Synthetic Financial Transaction Dataset
Source: Mendeley Data Repository

Contains:

Transaction amount

Device type

Merchant category

Location

Transaction time

Fraud label

Used for behavioral and anomaly detection research.

📁 Project Structure

fraud_detection_project/ – Main Django project
ml_app/ – ML models, views, and preprocessing
templates/ – Frontend HTML files
static/ – CSS and JS files
model.pkl – Trained hybrid ML model
db.sqlite3 – Default database
manage.py – Django command-line tool
