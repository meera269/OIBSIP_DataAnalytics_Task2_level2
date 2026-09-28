# OIBSIP_DataAnalytics_Task2_level2
Wine quality prediction using machine learning classification models (Random Forest, SVC, SGD) based on physicochemical wine properties.
## 📌 Objective
To train and evaluate multiple classification models (Random Forest, SGD, and SVC) to predict wine quality score based on physicochemical attributes such as acidity, density, alcohol content, and sulphates.

---

## 🛠️ Tools & Tech Stack
- **Language:** Python
- **Environment:** Jupyter Notebook (Anaconda Distribution)
- **Machine Learning:** `scikit-learn` (RandomForestClassifier, SGDClassifier, SVC, StandardScaler)
- **Visualization:** `matplotlib`, `seaborn`

---

## 📊 Steps Performed
1. **EDA & Imbalance Analysis:** Checked distributions of chemical properties and addressed class imbalance across quality ratings (3–8).
2. **Feature Engineering:** Binned quality scores into binary classification targets (`Good`: >= 7, `Bad/Average`: < 7).
3. **Stratified Split & Scaling:** Split data into training and testing sets with stratification and applied `StandardScaler`.
4. **Model Training & Evaluation:** Trained Random Forest, SGD, and SVC models; evaluated accuracy, confusion matrices, and classification reports.
5. **Feature Importance:** Plotted feature importance scores for the Random Forest model.

---

## 💡 Outcome
- **Best Model:** Random Forest Classifier achieved the highest accuracy (~90%+).
- **Key Indicators:** `alcohol`, `sulphates`, and `volatile acidity` were identified as the primary chemical predictors of high wine quality.

---

## 👤 Author
- **Intern:** Meerab Khan
- **Domain:** Data Analytics
- **Task:** Level 2 - Task 2
- **Organization:** Oasis Infobyte
