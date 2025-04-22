🚑 Infection Prediction using Logistic Regression

This project uses a **Logistic Regression** model to predict whether a person is infected based on symptoms like fever, age, runny nose, and difficulty in breathing. The dataset was preprocessed, explored, and split to train a binary classification model. Evaluation metrics were used to assess model performance.

---

📁 Dataset  
The dataset used is `tested.csv`, which contains the following features:

- **Fever**: Body temperature in Fahrenheit  
- **BodyPain**: Binary (1 if the person has body pain, 0 otherwise)  
- **Age**: Age of the individual  
- **RunnyNose**: Binary (1 if yes, 0 if no)  
- **DifficultyInBreath**: Binary (1 if yes, 0 if no)  
- **Infection**: Target variable (1 = Infected, 0 = Not Infected)  

---

🔍 Exploratory Data Analysis (EDA)  
- Checked dataset balance and structure  
- Observed the distribution of features using histograms  
- Analyzed correlations between variables  

---

🧪 Preprocessing  
- No missing values found in the dataset  
- Feature values were used as-is (no normalization or scaling required)  
- The dataset was split into training and testing sets (typically 80/20 split)

---

🤖 Model  
- **Algorithm**: Logistic Regression (from `sklearn.linear_model`)  
- Trained using `train_test_split`  
- Evaluation metrics used:
  - Accuracy Score  
  - Classification Report  
  - Confusion Matrix  

---

📊 Results  
- The model achieved good accuracy on the testing set  
- Confusion matrix showed decent balance between precision and recall  
- The model is simple and interpretable, suitable for basic health-risk predictions

---

📌 Libraries Used  
- `pandas`  
- `scikit-learn`  
- `matplotlib` (for visualization)  

---

✅ Author  
Yousef Sabry
