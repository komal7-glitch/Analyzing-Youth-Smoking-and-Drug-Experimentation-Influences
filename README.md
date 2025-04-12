# Analyzing-Youth-Smoking-and-Drug-Experimentation-Influences
# 🚬 Analyzing Youth Smoking and Drug Experimentation Influences

This project explores the factors influencing smoking and drug experimentation among youth using a dataset sourced from Kaggle. The aim is to uncover correlations, build predictive models, and offer actionable insights through a deployable Streamlit app.

📂 **Dataset**:  
[Youth Smoking and Drug Dataset on Kaggle](https://www.kaggle.com/datasets/waqi786/youth-smoking-and-drug-dataset)

---

## 📌 Objectives

- Identify key social, mental, and environmental factors influencing smoking and drug usage among youth.
- Predict smoking prevalence and classify risk levels for drug experimentation.
- Deploy an interactive Streamlit app for real-time analysis and prediction.

---

## 🛠️ Project Workflow

### 1. **Data Preprocessing**
- **Handle Missing Values** in crucial columns like `Smoking_Prevalence`, `Drug_Experimentation`, and `Mental_Health`.
- **Encode Categorical Variables**: Convert `Gender`, `Socioeconomic_Status`, and `Access_to_Counseling` into numeric values.
- **Scale Numeric Features**: Normalize fields such as `Peer_Influence`, `Mental_Health`, and `Community_Support`.

### 2. **Exploratory Data Analysis (EDA)**
- 📊 **Distribution Analysis** of `Smoking_Prevalence` and `Drug_Experimentation`.
- 🔍 **Correlation Analysis** among `Socioeconomic_Status`, `Family_Background`, `Parental_Supervision`, and `Mental_Health`.
- 👥 **Segment Analysis** across `Age_Group`, `Gender`, and `Socioeconomic_Status`.

### 3. **Model Building**
- 🔧 **Regression Model** (e.g., Linear Regression, Random Forest Regressor) to predict `Smoking_Prevalence`.
- 🧠 **Classification Model** (e.g., Logistic Regression, Decision Tree, Gradient Boosting) to classify risk level of `Drug_Experimentation`.

### 4. **Model Evaluation**
- 📐 **Regression Metrics**: Mean Absolute Error (MAE), R² Score.
- ✅ **Classification Metrics**: Accuracy, Precision, Recall, F1-score.
- 🔁 **Cross-Validation** for consistent model performance.

### 5. **Streamlit Deployment**
- 💻 **Streamlit App**:
    - Input demographic and behavioral features.
    - Visualize EDA results and predictions.
    - Real-time risk classification for drug experimentation.
- ☁️ **Deployment** on [Streamlit Community Cloud](https://streamlit.io/cloud) or locally using `streamlit run app.py`.

### 6. **Insights and Recommendations**
- 📌 Key risk indicators: low parental supervision, poor mental health, peer influence.
- 🧩 Recommendations:
    - Enhance community and family support systems.
    - Improve access to mental health and counseling services.
    - Run awareness programs for at-risk groups.

---

## 💡 Tech Stack

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Streamlit
- **Tools**: Jupyter Notebook, Streamlit, Git

---

## 📎 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🤝 Contribution

Feel free to fork the repo, open issues, or submit pull requests if you find bugs or want to contribute enhancements!

