<div align="center">
  <h1>🎯 Customer Churn Prediction</h1>
  <p>
    <em>Made with ❤️ by Sheick</em>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Python-3.12-blue.svg" alt="Python">
    <img src="https://img.shields.io/badge/Scikit--learn-1.6.0-orange.svg" alt="Scikit-learn">
    <img src="https://img.shields.io/badge/XGBoost-2.1.3-green.svg" alt="XGBoost">
    <img src="https://img.shields.io/badge/Streamlit-latest-red.svg" alt="Streamlit">
  </p>
</div>

## 📋 Overview

An advanced machine learning application that predicts customer churn probability using ensemble methods and provides personalized insights through an interactive Streamlit dashboard.

## 🌟 Features

- **Multi-Model Prediction System**

  - Random Forest
  - XGBoost
  - K-Nearest Neighbors
  - Ensemble Voting Classifier

- **Interactive Dashboard**

  - Real-time predictions
  - Dynamic visualization
  - Customer profile analysis
  - Personalized recommendations

- **Advanced Analytics**
  - Probability gauges
  - Feature importance analysis
  - Model comparison charts
  - AI-powered explanations

## 🛠️ Technical Stack

- **Frontend**: Streamlit
- **Backend**: Python 3.12
- **ML Libraries**:
  - scikit-learn
  - XGBoost
  - pandas
  - numpy
- **API Integration**: Groq API for AI explanations
- **Data Visualization**: Plotly

## 🚀 Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/Customer_Churn.git
cd Customer_Churn
```

2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Set up environment variables

```bash
cp .env.example .env
# Add your GROQ_API_KEY to .env
```

5. Run the application

```bash
streamlit run main.py
```

## 📊 Model Performance

| Model         | Accuracy | F1-Score | ROC AUC |
| ------------- | -------- | -------- | ------- |
| XGBoost       | 0.859    | 0.85     | 0.89    |
| Random Forest | 0.854    | 0.84     | 0.88    |
| KNN           | 0.832    | 0.82     | 0.85    |

## 🔍 Project Structure

```
Customer_Churn/
├── main.py              # Main Streamlit application
├── utils.py             # Utility functions
├── models/             # Trained ML models
├── churn.csv           # Dataset
├── requirements.txt    # Project dependencies
└── README.md          # Project documentation
```
