# 🩺 Diabetes Readmission Prediction Project

*A simple, practical machine learning project to predict if a diabetic patient will be readmitted to the hospital. This helps hospitals spot high-risk patients, improve care, and reduce costs.*

---

## 📌 What Does This Project Do?

- **Predicts** if a diabetic patient will be readmitted to the hospital soon after discharge.
- **Finds important factors** that lead to readmission.
- **Compares different machine learning models** to find the most accurate one.

---

## 🧠 What Tools Are Used?

- **Python** (programming language)
- **Jupyter Notebook** or **Google Colab** (for running code)
- **Libraries:**
  - `pandas`, `numpy` – for handling and analyzing data
  - `matplotlib`, `seaborn` – for making charts and graphs
  - `scikit-learn` – for machine learning models
  - `keras`, `tensorflow` – for deep learning (optional)

---

## 📊 What Data Is Used?

- **Diabetes Hospital Readmission Dataset** (over 100,000 patients)
- Includes:
  - Patient demographics (age, gender, etc.)
  - Lab results
  - Diagnosis codes
  - Treatment details
  - Hospital stay details
  - **Target:** Was the patient readmitted? ("<30", ">30", or "NO")

---

## 🔎 How Is The Data Explored?

- Check for missing or empty values
- See if the classes (readmitted/not) are balanced
- Visualize (plot) different features
- Find which features are related to each other
- Plot trends in patient readmissions

---

## ⚙️ How Is The Data Prepared?

- Turn text data into numbers (encoding)
- Pick the most useful features
- Fill in or remove missing values
- Balance the classes if needed (so the model isn’t biased)
- Split data into training and testing sets (usually 80/20 or 70/30)

---

## 🧪 Which Machine Learning Models Are Used?

- Logistic Regression
- Random Forest
- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes
- *(Optional)* Neural Networks (with Keras)

**How are models evaluated?**
- Accuracy
- Precision
- Recall
- F1-Score
- ROC AUC Score
- Confusion Matrix

---

## 🏆 What Are The Results?

| Model                | Accuracy | Precision | Recall | F1 Score |
|----------------------|----------|-----------|--------|----------|
| Random Forest        | 89%      | 87%       | 85%    | 86%      |
| Logistic Regression  | 84%      | 82%       | 80%    | 81%      |
| Decision Tree        | 81%      | 78%       | 76%    | 77%      |
| KNN                  | 75%      | 72%       | 70%    | 71%      |

> **Random Forest worked best, giving the highest F1-Score and was easy to interpret.**

---

## 📈 What Visualizations Are Included?

- How often patients are readmitted
- Which features are most important (Random Forest)
- Correlation heatmap (which features are related)
- Bar charts for top predictors
- Confusion matrix (shows model performance)

---

## 💡 What Did We Learn?

- Readmission is linked to number of medications, past hospital stays, and insulin use.
- Spotting high-risk patients early can improve care and save money.
- Creating new features and cleaning data makes models better.

---

## 📂 Project Structure

```
Diabetes_Readmission_Project/
├── Diabetes_Simulation_Project_(Diabetes_Dataset).ipynb
├── README.md
├── data/
│   └── diabetes_data.csv
├── models/
│   └── saved_model.pkl
└── requirements.txt
```

---

## 🚀 What’s Next?

- Try deep learning models like LSTM or ANN
- Deploy the model as a web app (Flask/Django/Streamlit)
- Connect to hospital systems for real-time predictions
- Explain predictions using SHAP or LIME

---

## 🤝 Thanks & Credits

Thanks to open-source contributors and medical data repositories, especially the UC Irvine Machine Learning Repository.

---

## 📬 Contact

**Poojitha Sajjavarapu**  
📧 saipoojithasajjavarapu@gmail.com  
💼 [LinkedIn](#) <!-- https://www.linkedin.com/in/sai-poojitha-sajjavarapu-b14906252 -->  
