# 🏋️‍♂️ Fitness Prediction Using Random Forest

This project uses a Random Forest Classifier to predict whether a person is **Fit** or **Not Fit** based on simple health and lifestyle metrics.

---

## 📊 Features Used

The dataset includes the following features:

- `Age` (years)
- `Height_cm` (centimeters)
- `Weight_kg` (kilograms)
- `HeartRate_bpm` (beats per minute)
- `StepsPerDay` (average daily steps)
- `StressLevel` (scale: 1 to 10)
- `SleepHours` (hours of sleep per night)
- `CaloriesIntake` (daily intake in kcal)
- `WaterIntake_Liters` (liters per day)
- `ExerciseMinutes` (minutes per day)
- `Smoker` (1 = Yes, 0 = No)
- `AlcoholUnitsPerWeek` (units per week)
- `IsFit` (1 = Fit, 0 = Not Fit) – **Target variable**

---

## 🧠 Model Used

- **Random Forest Classifier**
- Train/test split: `80/20`
- Standardized input features using `StandardScaler`

---

## ✅ Results

- **Accuracy**: ~85%
- **High recall for Not Fit class (important for health prediction)**
- **Feature Importance & ROC curve included**

---

## 📁 Files

- `Fit_or_not.csv` – Dataset file (upload in Colab)
- `Fit_or_not.ipynb` – Colab notebook for training & evaluation
- `README.md` – This file

---

## 🚀 How to Use

1. Launch Jupyter Notebook or VS Code with Jupyter extension
2. Open fitness_predictor.ipynb
3. Ensure fitness_data.csv is in the same folder
4. Run cells to:
   - Train the model
   - Evaluate performance
   - Visualize confusion matrix

---

## 📌 Next Steps

- Improve dataset balance using SMOTE or data augmentation
- Deploy model using Streamlit or Gradio for real-time predictions
- Save trained model using `joblib` or `pickle`