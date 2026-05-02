# 🧠Body Performance Analytics & Intelligent Classification System

> An end-to-end machine learning project that analyzes human body performance data, applies multiple AI models for classification and regression, and delivers insights through an interactive Streamlit web application.

---

## 📌 Project Overview

**AXORA** is a data science and applied AI project built around a body performance dataset. The project covers the full ML pipeline — from exploratory data analysis and data cleaning, to training and comparing multiple machine learning models, to deploying a polished interactive dashboard using Streamlit.

The system classifies physical fitness levels and predicts performance metrics based on features like age, gender, body fat percentage, grip strength, flexibility, and cardiovascular endurance.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python** | Core programming language |
| **Streamlit** | Interactive web application & dashboard |
| **Scikit-learn** | ML model training & evaluation |
| **Pandas / NumPy** | Data manipulation & preprocessing |
| **Matplotlib / Seaborn** | Data visualization & EDA plots |
| **Jupyter Notebook** | Model experimentation & analysis |

---

## 🤖 ML Models Implemented

| Model | Type | Notebook |
|-------|------|---------|
| **KNN** | Classification + Regression | `KNN_classification_notebook_.ipynb` / `KNN_Regression_notebook_.ipynb` |
| **Decision Tree** | Classification | `Decision tree Final.ipynb` |
| **SVM** | Classification | `1_SVM_85_.ipynb` |
| **Neural Network** | Classification | `NN_body_performance_two_layer_.ipynb` |
| **Linear Regression** | Regression | `linear_regresion_Body_Performance.ipynb` |

---

## 📁 Project Structure

```
Body-Performance-Analytics-and-Intelligent/
│
├── 📱 axora_app_v9.py                  # Main Streamlit app (latest version)
├── 📱 axora_app_v8.py                  # Previous app version
├── 📋 requirements.txt                 # Python dependencies
│
├── 5_MODEL_AI/
│   ├── 🤖 Decision Tree/
│   │   └── Decision tree Final.ipynb
│   ├── 🤖 KNN/
│   │   ├── KNN_classification_notebook_.ipynb
│   │   └── KNN_Regression_notebook_.ipynb
│   ├── 🤖 Linear Regression/
│   │   └── linear_regresion_Body_Performance.ipynb
│   ├── 🤖 Neural Network/
│   │   └── NN_body_performance_two_layer_.ipynb
│   ├── 🤖 SVM/
│   │   └── 1_SVM_85_.ipynb
│   ├── 📓 classification_notebook_eda.ipynb
│   ├── 📓 regression_notebook.ipynb
│   ├── 📄 Axora_ML_Report_v5.pdf       # Full ML report
│   └── 🎨 axora_team_logo.svg
```

---

## 🖥️ AXORA App Features

The Streamlit app includes 5 main sections:

- **🏠 Home** — Branded landing page with team logo
- **📊 Data Overview** — Dataset preview, shape, column types, and statistics
- **📈 EDA** — Interactive exploratory data analysis with visualizations
- **🤖 Model Analysis** — Compare performance metrics across all 5 ML models (accuracy, precision, recall, F1, confusion matrix)
- **🎯 Prediction** — Real-time fitness classification based on user input

### App Design
- Dark theme UI (`#0B1621` background) with blue accent palette (`#3B8BD4`, `#4CC9F0`)
- Custom fonts: Orbitron (headings) + Inter (body)
- Responsive metric cards, styled tables, and section headers

---

## 🚀 How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/Body-Performance-Analytics-and-Intelligent.git
cd Body-Performance-Analytics-and-Intelligent

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
streamlit run "axora_app_v9 (4).py"
```

---

## 📊 Dataset Features

The body performance dataset includes:

| Feature | Description |
|---------|-------------|
| `age` | Age of the individual |
| `gender` | Male / Female |
| `height_cm` | Height in centimeters |
| `weight_kg` | Weight in kilograms |
| `body fat_%` | Body fat percentage |
| `diastolic` | Diastolic blood pressure |
| `systolic` | Systolic blood pressure |
| `gripForce` | Grip strength measurement |
| `sit and bend forward_cm` | Flexibility test |
| `sit-ups counts` | Core strength |
| `broad jump_cm` | Explosive power |
| `class` | Performance class (A / B / C / D) — **Target variable** |

---

## 👩‍💻 Author

**Aya Shaaban Gameel**
Junior Data Analyst | Chemistry Background → Data Analytics
Specializing in SQL, Power BI, Python & Applied AI in Healthcare

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-blue?style=flat-square)](https://preview--chem-to-code-folio.lovable.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com)

---

## 👥 Team

This project was built by **Team Axora** as part of an applied AI & data analytics program.

---

## 📃 License

For educational and portfolio purposes only.
