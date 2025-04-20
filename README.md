# Dissertation
# Leveraging AI for Application Rationalization using Conversational Interfaces

This project presents an intelligent solution for Application Rationalization within Enterprise Architecture by combining Machine Learning (ML) and Natural Language Processing (NLP) through a chatbot interface. The solution assists stakeholders in determining whether to **Invest**, **Retire**, **Migrate**, or **Sustain** business applications based on various assessment indicators.

---

## 🔍 Overview

The system integrates:
- A **Machine Learning Model** for disposition prediction using application indicators.
- A **RASA-powered Chatbot** for interactive, conversational support.
- A **SQLite Database** to store application information and demand records.

---

## 🛠️ Technologies Used

### Machine Learning
- Algorithms: XGBoost (final model), Random Forest, Logistic Regression, SVM
- Tools: Python, Scikit-learn, Pandas, XGBoost
- Model Files: `selector.pkl`, `scaler.pkl`, `xgb_model.pkl`

### Natural Language Processing (Chatbot)
- Framework: [RASA](https://rasa.com/)
- Features: Intent recognition, entity extraction, dialogue management

### Backend & Database
- SQLite for storing business application and demand data



