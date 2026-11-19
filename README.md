# 🫀 Cardio Vue AI
### Intelligent Cardiovascular Risk Prediction & Monitoring

Cardio Vue AI is an AI-powered cardiovascular disease risk prediction and monitoring platform that combines machine learning, data analytics, and an interactive web interface to support patients, doctors, and medical researchers.

The platform uses machine learning models to assess cardiovascular risk and provides tools for health monitoring, research analysis, and clinical insights.

## 🌐 Live Demo
[Try Cardio Vue AI](https://cardiovueai.streamlit.app/)

## ✨ Key Features

- **Cardiovascular Risk Prediction:** Predicts cardiovascular disease risk using machine learning.
- **Ensemble Machine Learning:** Uses multiple ML models and a stacking ensemble approach.
- **Patient Dashboard:** Provides health records, appointments, goals, and notifications.
- **Doctor Dashboard:** Supports patient management and clinical risk assessment.
- **Research Hub:** Provides research-related tools and analytics.
- **What-If Analysis:** Allows users to explore how changes in health factors may affect predicted risk.
- **AI Health Assistant:** Provides an interactive health-related chatbot.
- **Literature Review:** Supports medical research and literature exploration.
- **Data Visualization:** Displays model performance, confusion matrices, feature importance, and comparison charts.
- **Clinical Guidelines:** Provides access to clinical guideline information.

## 🤖 Machine Learning Models

The project includes implementations and evaluation outputs for:

- XGBoost
- CatBoost
- Extreme Random Forest
- Neural Network
- Stacking Ensemble

Model performance is evaluated using metrics such as:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Specificity

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Programming | Python |
| Frontend | Streamlit |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn, XGBoost, CatBoost |
| Visualization | Plotly, Matplotlib, Seaborn |
| Database | SQLite |
| Model Utilities | Joblib |
| PDF Generation | FPDF |

## 📂 Project Structure

```text
AI-ML-PROJECT/
│
├── app.py
├── model_training.py
├── requirements.txt
│
├── data/
│   └── kaggle_heart.csv
│
├── modules/
│   ├── clinical_guidelines_viewer.py
│   ├── doctor_pages.py
│   ├── literature_review.py
│   ├── patient_pages.py
│   ├── research_hub.py
│   ├── researcher_pages.py
│   ├── shared_navigation.py
│   └── whatif_page.py
│
├── utils/
│   ├── ai_chatbot.py
│   ├── clinical_guidelines.py
│   ├── database.py
│   ├── literature_db.py
│   ├── ml_engine.py
│   ├── pdf_report.py
│   └── theme.py
│
├── results/
├── tests/
└── visualizations/
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/pluto-droid/AI-ML-PROJECT-.git
```

### 2. Navigate to the project directory

```bash
cd AI-ML-PROJECT-
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
streamlit run app.py
```

The application will open in your browser.

## 👩‍💻 My Contribution

**Role: Research & Machine Learning Developer**

My primary contribution to Cardio Vue AI was focused on the Research and Machine Learning components.

- Developed research-related interfaces, including the Research Hub, researcher dashboard, dataset explorer and model laboratory.
- Worked on literature review functionality, including research paper searching, filtering and database integration.
- Contributed to the machine learning pipeline, including data preprocessing, feature engineering, handling class imbalance, model training and evaluation.
- Worked on ML prediction functionality, including model loading, cardiovascular risk prediction and SHAP-based explainability.
- Contributed to model performance analysis and visualizations using metrics such as accuracy, precision, recall, F1-score and ROC-AUC.
- Worked on integrating research and ML components into the overall application.

**Key Areas:** Python, Machine Learning, Scikit-learn, XGBoost, CatBoost, Streamlit, Pandas and SHAP.

## ⚠️ Disclaimer

Cardio Vue AI is an educational and research-oriented project. Its predictions are not a substitute for professional medical diagnosis, advice, or treatment.

## 👥 Project Credits

Developed collaboratively as an AI and Machine Learning project.

**Repository:** [Anmol's GitHub](https://github.com/pluto-droid)
