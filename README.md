✈️ Airplane Crash Probability Predictor
A Streamlit web application that predicts the probability of an airplane crash based on aircraft model, airline operator, and year. This project is built using Machine Learning classifiers (Decision Tree, Random Forest, XGBoost) and aims to provide insights using historical aviation accident data.

🚀 Demo
Run locally: http://localhost:8501
(After executing streamlit run app.py)

📊 Dataset
Source: ICAO Crash Dataset (2008–2022)

Preprocessed columns used:

Date

Model (Aircraft type)

Operator (Airline)

Year (Extracted from Date)

crash (Target: 1 for crash, 0 for no crash)

🧠 Features
Interactive UI built using Streamlit

Predicts crash probability using XGBoost model

Encodes categorical variables using LabelEncoder

Automatically retrains model on dataset load

Displays crash probability in real-time for selected inputs

🛠️ Installation
Clone the repository or download this folder:

bash
Copy
Edit
git clone https://github.com/yourusername/airplane-crash-predictor.git
cd airplane-crash-predictor
Install the required Python libraries:

bash
Copy
Edit
pip install -r requirements.txt
Or manually:

bash
Copy
Edit
pip install pandas scikit-learn xgboost streamlit
Ensure that your cleaned dataset is saved as:

Copy
Edit
icao_crash_dataset.csv
Place it in the same directory as app.py.

▶️ Running the App
From your terminal or PowerShell:

bash
Copy
Edit
cd "C:\Users\yourname\Documents\PlaneCrash"
streamlit run app.py
Visit: http://localhost:8501

📷 App Preview
(Insert screenshot here: screenshot.png)

🤖 Model Details
Classifiers used:

Decision Tree

Random Forest

XGBoost (primary model)

Categorical encoding: LabelEncoder

Evaluation metrics: Accuracy, Precision, Recall, F1-score

Input features: Aircraft Model, Operator, Year

⚠️ Disclaimer
This is a predictive analytics educational project.
The results are based solely on historical crash data and should not be interpreted as real-world flight risk evaluations.

👩‍💻 Author
Akshaya Badugu

B.Tech CSE (AI/ML), 4th Year

📃 License
This project is licensed under the MIT License.

