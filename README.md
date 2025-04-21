🩺 Diabetes Risk Prediction System
A user-friendly web app that predicts the risk of diabetes based on patient health indicators using machine learning models such as Random Forest and Support Vector Machine (SVM). Built with Python, Scikit-learn, Pandas, Streamlit, and Matplotlib.

🚀 Features
📥 Upload and preprocess diabetes health indicator datasets

📊 Exploratory Data Analysis (EDA) with summary stats and heatmaps

🤖 Train and evaluate models (Random Forest and SVM with GridSearchCV)

🎯 Predict diabetes risk using a sidebar form for user input

📈 Interactive and responsive interface with visualizations and metrics

📦 Dataset Sources
The app utilizes the following datasets:

diabetes_012_health_indicators_BRFSS2015.csv

diabetes_binary_5050split_health_indicators_BRFSS2015.csv

diabetes_binary_health_indicators_BRFSS2015.csv

These datasets are preloaded and concatenated for use.

🔧 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/diabetes-prediction-app.git
cd diabetes-prediction-app
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
🧪 Model Training and Evaluation
Models used:

Random Forest Classifier

Support Vector Classifier (SVC)

Hyperparameter tuning with GridSearchCV

Metrics used:

ROC-AUC

Precision

Recall

F1-Score

🧠 Prediction Interface
Users can input various health metrics (like BMI, blood pressure, alcohol use, physical activity, etc.)

The app returns the diabetes risk probability for each model

Metrics are shown in a clean and interactive way

📁 File Structure
bash
Copy
Edit
📂 diabetes-prediction-app/
│
├── app.py                     # Main Streamlit application
├── requirements.txt           # Required Python packages
├── README.md                  # Project documentation
├── 📂 data/
│   └── *.csv                  # Diabetes datasets
✅ Requirements
Python 3.7+

Streamlit

Pandas

NumPy

Scikit-learn

Seaborn

Matplotlib
