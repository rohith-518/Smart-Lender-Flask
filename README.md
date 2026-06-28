# Smart Lender - Loan Approval Prediction

## Overview
Smart Lender is a Machine Learning web application built with Flask that predicts whether a loan application is likely to be approved based on applicant details. The application uses a trained Random Forest model to provide instant loan approval predictions.

## Features
- Loan approval prediction
- User-friendly web interface
- Random Forest Machine Learning model
- Fast and accurate predictions
- Responsive design

## Technologies Used
- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- HTML
- CSS

## Project Structure

```
Smart-Lender/
│── app.py
│── rdf.pkl
│── scale1.pkl
│── requirements.txt
│
├── templates/
│   ├── home.html
│   ├── input.html
│   └── output.html
│
└── static/
    └── css/
        └── input.css

```
# 🎥 Demo Video

## Smart Lender – Loan Eligibility Prediction System

Watch the demo video of our project here:

https://youtu.be/ifRnALTWhpY?si=OgtR7x0N-m9j9lsL
## Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the application

```bash
python app.py
```

4. Open your browser

```
http://127.0.0.1:5000
```

## Input Features

- Gender
- Married
- Dependents
- Education
- Self Employed
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

## Output

The application predicts:

- ✅ Loan Approved
- ❌ Loan Rejected

## Machine Learning Model

- Random Forest Classifier

## Author

Rohith Perisetti
