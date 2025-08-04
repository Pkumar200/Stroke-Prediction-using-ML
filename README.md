🧠 Stroke Prediction using Machine Learning

This project uses a Machine Learning model to predict the likelihood of a stroke based on patient demographic and health data. Built using Python in a Jupyter Notebook, it demonstrates a complete ML pipeline from data preprocessing to model evaluation.

📂 Project Files

- stroke_prediction.ipynb – Main Jupyter Notebook with code and visualizations.
- requirements.txt – List of Python packages needed to run the notebook.
- .gitignore – Specifies files/folders to be excluded from Git commits.
- stroke_data.csv – Dataset used (not included in the repo if it's large/private).

🚀 How to Run the Project

1. Clone the repository:

git clone https://github.com/Pkumar200/Stroke-Prediction-using-ML.git
cd Stroke-Prediction-using-ML

2. Install required packages:

pip install -r requirements.txt

3. Open the notebook:

jupyter notebook stroke_prediction.ipynb

🔬 Machine Learning Pipeline

- Data Cleaning
- Handling Missing Values
- Label Encoding for Categorical Features
- Feature Scaling
- Train-Test Split
- Model Training using Random Forest
- Evaluation: Accuracy, Confusion Matrix, Classification Report

📊 Dataset

- Source: Kaggle - Stroke Prediction Dataset (https://www.kaggle.com/fedesoriano/stroke-prediction-dataset)
- Features: age, gender, hypertension, heart disease, ever_married, work_type, Residence_type, avg_glucose_level, bmi, smoking_status

✅ Sample Output

- Accuracy: ~95% (may vary based on data split and model)
- Model Used: Random Forest Classifier
- Metrics: Accuracy, Precision, Recall, F1-score

👨‍💻 Author

P. Kumaraswamy
GitHub: @Pkumar200 (https://github.com/Pkumar200)

📃 License

This project is for educational purposes only. The dataset used may be subject to its own license terms as defined on Kaggle.
