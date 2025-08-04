# Medicine_Recommendation_System
This Repository contains the implementation of medicine recommendation and disease prediction system.
# Introduction
The System predict disease and recommend medicine based on user entered symptoms. The system provides the recommendations for medications,diets and workouts. The project uses a datasets from a kaggle.
# Project Overview
## 1. Kaggle Datasets
- `description.csv` : Description for diseases.
- `diets.csv` : Suggest diets for diseases.
- `medications.csv` : Prescribed medications related to diseases.
- `precautions_df.csv` : What precautions we take for diseases.
- `Symptom-severity.csv` : Severity of symptoms.
- `symptoms_df.csv` : Symptoms with disease labels.
- `Training.csv` : Dataset for training machine learning models.
- `workout_df.csv` : Recommended workouts for diseases.

## 2. model
- `RandomForest.pkl` : Trained random forest model for disease prediction.

## 3. static
- `heart_17879064.png`, `medical_13306878.png`, `medical-equipment-with-copy-space.jpg` : Images are used for frontend.

## 4. templates
- `index.html` : Frontend interface for the system.

# How to Run the Project
To run the Medicine Recommendation System.
## 1. Install required Python libraries:
```
pip install -r requirements.txt
```
## 2. Start the Flask application :
```
python main.py
```
## 3. Access the web interface in your browser at :
```
 http://127.0.0.1:5000
```
# Project Files Overview 
- `main.py` : Entry point for the web application.
- `Medicine_pred-checkpoint.ipynb` : Jupyter notebook with model training and data preprocessing.
