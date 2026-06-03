# 🏏 IPL Win Predictor

<div align="center">

# 📊 AI-Powered IPL Match Win Probability Predictor

Predict the winning probability of IPL teams in real-time using Machine Learning and live match statistics.

Built with:

* 🧠 Machine Learning
* 📈 Scikit-Learn
* 🎨 Streamlit
* 🐍 Python
* 📊 Pandas

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-FF4B4B?style=for-the-badge\&logo=streamlit)
![Scikit Learn](https://img.shields.io/badge/ML-ScikitLearn-F7931E?style=for-the-badge\&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Data-Pandas-150458?style=for-the-badge\&logo=pandas)

</div>

---

# 🌟 Project Overview

IPL Win Predictor is a machine learning-powered web application that predicts the probability of a team winning an IPL match based on the current match situation.

The application analyzes real-time match conditions such as:

* Target score
* Current score
* Overs completed
* Wickets fallen
* Runs required
* Current Run Rate (CRR)
* Required Run Rate (RRR)

and generates winning probabilities for both teams.

---

# ✨ Features

## 🏏 Match Prediction Features

* ✅ Real-time win probability prediction
* ✅ Team vs Team analysis
* ✅ Live match situation input
* ✅ Dynamic win percentage calculation
* ✅ Probability-based predictions

---

## 🎨 User Interface Features

* ✅ Clean Streamlit interface
* ✅ Interactive input forms
* ✅ Progress bars
* ✅ Percentage indicators
* ✅ Responsive design

---

## 🤖 Machine Learning Features

* ✅ Pre-trained prediction model
* ✅ Probability-based output
* ✅ Feature engineering
* ✅ Classification pipeline
* ✅ Fast prediction response

---

# 🧠 Machine Learning Model

The application uses a trained machine learning pipeline stored in:

```text
pipe.pkl
```

The model predicts match outcomes using:

* Batting Team
* Bowling Team
* Match City
* Runs Left
* Balls Left
* Wickets Left
* Current Run Rate
* Required Run Rate

---

# 📊 Prediction Workflow

```text
User Inputs Match Details
           ↓
Feature Engineering
           ↓
Machine Learning Pipeline
           ↓
Probability Calculation
           ↓
Win Percentage Output
```

---

# 🛠️ Technology Stack

| Component        | Technology               |
| ---------------- | ------------------------ |
| Frontend         | Streamlit                |
| Language         | Python                   |
| Data Processing  | Pandas                   |
| Machine Learning | Scikit-Learn             |
| Model Storage    | Pickle                   |
| Deployment       | Streamlit Cloud / Heroku |

---

# 📂 Project Structure

```bash
IPL-Win-Predictor/
│
├── app.py
├── pipe.pkl
├── requirements.txt
├── Procfile
├── setup.sh
├── README.md
│
└── assets/
```

---

# ⚙️ Installation & Setup

## 📌 Prerequisites

Install:

* Python 3.x
* pip
* Git

---

# 🚀 Setup Instructions

## 1️⃣ Clone Repository

```bash
git clone https://github.com/singhshrasti/IPL-Win-Probability-Predictor.git
```

```bash
cd IPL-Win-Probability-Predictor
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run Application

```bash
streamlit run app.py
```

---

# 🌐 Open Application

```text
http://localhost:8501
```

---

# 📊 Input Parameters

The model requires the following inputs:

| Parameter       | Description            |
| --------------- | ---------------------- |
| Batting Team    | Team currently batting |
| Bowling Team    | Team currently bowling |
| City            | Match venue            |
| Target          | Target score           |
| Score           | Current batting score  |
| Overs Completed | Overs played           |
| Wickets Out     | Wickets fallen         |

---

# 📈 Engineered Features

The system calculates:

### Runs Left

```text
Target - Current Score
```

### Balls Left

```text
120 - Balls Played
```

### Wickets Left

```text
10 - Wickets Fallen
```

### Current Run Rate

```text
Current Score ÷ Overs Played
```

### Required Run Rate

```text
Runs Left ÷ Overs Remaining
```

---

# 🎯 Use Cases

* IPL match analysis
* Cricket enthusiasts
* Sports analytics projects
* Machine learning demonstrations
* Educational projects

---

# 🧪 Testing

## ✅ Tested Functionalities

* Team selection
* Probability prediction
* Feature calculations
* UI rendering
* Model loading

---

# 🔮 Future Enhancements

* 📡 Live IPL API integration
* 📱 Mobile-friendly interface
* 🏆 Match history analysis
* 📈 Team performance analytics
* 🤖 Deep learning models
* 🌐 Multi-league support

---

# 📜 License

This project is developed for:

* Educational purposes
* Machine learning practice
* Sports analytics research

---

# ❤️ Credits

Built using:

* Python
* Streamlit
* Scikit-Learn
* Pandas
* Pickle

---

# 👨‍💻 Developer

```text
Surya
Machine Learning Enthusiast | Full Stack Developer
```

---

# 🤝 Contributing

Contributions are welcome!

## Steps

```bash
Fork → Clone → Create Branch → Commit → Push → Pull Request
```

---

# ⭐ Support

If you like this project, please ⭐ the repository!

---

<div align="center">

# 🏏 Predict Every Run. Predict Every Match.

📊 AI-Powered IPL Match Prediction using Machine Learning

</div>
