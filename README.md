📘 Study Group Prediction using Machine Learning

🔎 Overview This project predicts whether a student is likely to join a study group based on their attendance and exam score.
It’s a simple but powerful demonstration of the full machine learning workflow: data preparation, model training, evaluation, cross‑validation, hyperparameter tuning, and visualization.

📊 Dataset

Features:
Attendance (percentage)
ExamScore (numeric score)
Target:
StudyGroup (Yes = 1, No = 0)
Size: Small, synthetic dataset created for practice.
⚙ Methods

Data Preprocessing

Train/Test split (80/20)
Encoding categorical target
Scaling not required (features already numeric)
Models Trained

Logistic Regression
Decision Tree
Random Forest
Evaluation

Accuracy, Precision, Recall, F1‑score
Cross‑validation (5‑fold)
Hyperparameter tuning with GridSearchCV
Visualization

Logistic Regression decision boundary
Decision Tree structure
Random Forest feature importance
✅ Results

Accuracy (all models): 1.0 on test set
Cross‑validation mean score: ~0.98
Key insight: Attendance and Exam Score are strong predictors of study group membership.
📈 Key Learnings

Small, clean datasets can produce perfect accuracy.
Cross‑validation is essential for reliable performance estimates.
Hyperparameter tuning may not improve results if the dataset is simple.
Visualizations make models easier to interpret and explain.
🚀 Next Steps

Apply workflow to larger, noisier datasets.
Explore additional models (e.g., SVM, Gradient Boosting).
Extend features (study hours, assignments, etc.).
Transition to Project 1: HealthTech – Predictive Health Risk App.
🛠 How to Run `bash

Install dependencies

    pip install -r requirements.txt
Run the notebook or script python studygroupprediction.py `

🙏 Acknowledgments This project was created as a learning exercise to practice machine learning fundamentals and prepare for larger applied projects.

