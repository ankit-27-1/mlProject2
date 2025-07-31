📊 Student Performance Indicator
A complete end-to-end Machine Learning project to predict student math scores based on various demographic and educational factors.

🚀 Overview
This project aims to analyze and predict student performance using regression models. It covers all phases of a typical ML project lifecycle — from data ingestion to model deployment.

🧠 Problem Statement
Predict a student's math score based on:

Gender

Ethnicity

Parental level of education

Lunch type

Test preparation course

Reading & Writing scores

📂 Project Structure
bash
Copy
Edit
.
├── data/                       # Raw dataset (CSV)
├── notebook/                  # EDA and visualization
├── src/                       # Source code package
│   ├── components/            # Data processing, transformation, and model training
│   ├── logger.py
│   ├── exception.py
│   └── utils.py
├── artifacts/                 # Saved model & preprocessor
├── train_pipeline.py         # Training entry point
├── predict_pipeline.py       # Prediction script
📊 Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn, XGBoost, CatBoost, Random Forest

Pickle, Logging, Exception handling

✅ Features
EDA & insights using Seaborn

Outlier detection and missing value handling

Robust preprocessing pipelines

Model comparison & evaluation

Saved best model (R² > 0.9)

📈 Model Performance
Best performing model: CatBoost Regressor
R² Score: > 0.9

🗃️ Dataset
Kaggle: Student Performance Dataset

🧪 Run Locally
bash
Copy
Edit
git clone https://github.com/your-username/student-performance-indicator.git
cd student-performance-indicator
python train_pipeline.py
✍️ Author
Ankit Kumar Jha
LinkedIn • GitHub

