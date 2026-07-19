# 📈 CashForecast

CashForecast is an AI-powered financial forecasting and planning platform that helps users analyze their financial health by processing bank transaction data, predicting future cash flow, detecting spending trends, and delivering proactive financial insights through an interactive dashboard.

**Live Demo:** https://cashpredictor.onrender.com/

> **Note:** The application is hosted on Render's free tier and may take a few moments to wake up after periods of inactivity.

---

# Overview

CashForecast was developed during a hackathon to simplify personal financial planning using data analytics, predictive modeling, and intelligent automation.

Unlike traditional expense trackers that only display historical transactions, CashForecast analyzes user spending behavior, predicts future cash flow, identifies financial risks, and proactively notifies users before potential financial problems occur.

The platform allows users to:

* Upload financial statements (CSV/PDF)
* Analyze spending patterns
* Predict future cash flow
* Detect financial trends
* Receive automated financial alerts
* Explore investment planning
* Analyze insurance coverage
* View insights through an interactive dashboard

---

# My Contributions (Akshata Naik)

I was responsible for building the core machine learning pipeline, forecasting engine, backend integration, automated email notification system, and several backend enhancements that power the financial analysis workflow.

## Machine Learning & Forecasting

* Built and integrated the core financial forecasting model.
* Designed the complete machine learning pipeline from preprocessing to prediction.
* Developed model training workflows using historical financial transaction datasets.
* Integrated forecasting models with the Flask backend.
* Improved preprocessing pipelines and feature engineering for better prediction accuracy.

---

## Data Processing Pipeline

* Developed the foundational data processing workflow.
* Implemented data cleaning and normalization for uploaded bank statements.
* Built preprocessing pipelines for structured financial analysis.
* Connected uploaded datasets directly to the prediction engine.
* Created the base architecture used for model training.

---

## Backend Development

* Developed major portions of the Flask backend.
* Implemented backend APIs and core business logic.
* Connected machine learning models with frontend workflows.
* Managed backend integration between uploaded data, predictions, and dashboard analytics.
* Assisted in overall system integration and backend optimization.

---

## Autonomous Email Alert System

One of my major contributions was implementing the proactive financial notification system.

Instead of requiring users to continuously monitor the dashboard, CashForecast automatically detects risky financial trends and sends warning emails whenever predefined financial conditions are met.

### Workflow

```text
User Uploads Financial Data
            │
            ▼
Financial Analysis Engine
            │
            ▼
Trend Detection
            │
            ▼
Alert Generation
            │
            ▼
SMTP Email Service
            │
            ▼
User Email Inbox
```

### Features

* Implemented the complete email notification workflow.
* Integrated Python SMTP with Gmail SMTP Server.
* Configured secure authentication using environment variables.
* Automated financial alert generation.
* Personalized email notifications for each registered user.
* Added Demo Mode support when SMTP credentials are unavailable.
* Ensured secure credential management without hardcoding sensitive information.

### Technologies Used

* Python SMTP
* Gmail SMTP
* Flask
* Environment Variables
* Secure App Password Authentication

---

## Dashboard Integration

* Connected forecasting results with dashboard visualizations.
* Implemented backend calculations for financial analytics.
* Integrated machine learning outputs into dashboard reports.
* Connected backend analytics with frontend visualizations.

---

## Product Enhancements

* Added backend feature enhancements.
* Fixed bugs and improved application stability.
* Optimized existing workflows.
* Supported project integration and testing.

---

# Project Features

## Financial Forecasting

* Historical spending analysis
* Cash flow prediction
* Future balance forecasting
* Forecast visualization

## Investment Planning

* Investment analysis tools
* Risk evaluation
* Return estimation
* Long-term financial planning

## Insurance Planning

* Insurance recommendation workflows
* Financial protection analysis
* Coverage planning assistance
* Protection gap analysis

## Interactive Dashboard

* Financial health overview
* Spending insights
* Key financial metrics
* Interactive charts and reports

## Data Processing

* CSV file support
* PDF statement processing
* Data normalization
* Automated preprocessing pipeline

## Smart Email Notifications

* Automatic financial alerts
* Spending trend detection
* Personalized email notifications
* Demo Mode support

---

# Technology Stack

| Layer            | Technologies                                    |
| ---------------- | ----------------------------------------------- |
| Backend          | Python, Flask, Flask-SQLAlchemy                 |
| Machine Learning | Pandas, NumPy, Scikit-learn, SciPy, StatsModels |
| Data Processing  | PDFPlumber, Python Dateutil                     |
| Frontend         | HTML, CSS, JavaScript                           |
| Visualization    | Chart.js                                        |
| Email Service    | Python SMTP, Gmail SMTP                         |
| Database         | SQLite                                          |
| Deployment       | Render                                          |

---

# System Workflow

```text
                User Uploads Statement
                         │
                         ▼
          Data Processing & Cleaning
                         │
                         ▼
          Financial Analysis Engine
                         │
      ┌──────────┬────────────┬────────────┐
      │          │            │            │
      ▼          ▼            ▼            ▼
 Forecast   Investment   Insurance   Dashboard
      │
      ▼
 Trend Detection
      │
      ▼
 Email Alert Service
      │
      ▼
 Dashboard + User Email
```

---

# Team

| Member        |
| ------------- |
| Akshata Naik  |
| Priyesh Shah  |
| Sameer Musani |
| Umang Yadav   |

---

# Future Improvements

* Advanced machine learning forecasting models
* Deep learning-based financial prediction
* PostgreSQL database integration
* Cloud-native deployment
* Improved financial recommendation engine
* Enhanced analytics dashboard
* Portfolio optimization
* Mobile application support
* Real-time banking API integration
* Scheduled financial health reports

---

# License

Developed as a hackathon project for educational and demonstration purposes.
