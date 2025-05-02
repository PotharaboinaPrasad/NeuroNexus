# NeuroNexus
This project predicts whether a passenger survived the Titanic disaster using machine learning. The dataset used contains details like age, gender, class, and more to train a classification model. The model is built using Python, pandas, and scikit-learn.

📂 Dataset
The dataset (tested.csv) is a cleaned version of the Titanic dataset with the following features:

Pclass – Passenger class (1st, 2nd, 3rd)

Sex – Gender of the passenger

Age – Age of the passenger

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Fare – Ticket fare

Embarked – Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Survived – Target variable (0 = No, 1 = Yes)

⚠️ Missing values are handled using median (for Age) and mode (for Embarked).

🧠 Model
A Random Forest Classifier is used to predict survival. It provides good performance for structured/tabular data and handles both numerical and categorical features well.

Key Steps:
Load and clean the data

Encode categorical variables

Train/test split

Train RandomForestClassifier

Evaluate model accuracy and classification metrics

📈 Evaluation
The model is evaluated using:

Accuracy Score

Classification Report (Precision, Recall, F1-Score)

🚀 Getting Started
Requirements
Python 3.x

pandas

scikit-learn

Installation
bash
Copy
Edit
pip install pandas scikit-learn
Run the project
bash
Copy
Edit
python titanic_model.py
Replace titanic_model.py with your script filename.

📊 Output
The script prints:

Model accuracy

Detailed classification report

Sample predictions (optional)

📌 Future Improvements
Hyperparameter tuning (GridSearchCV or RandomizedSearchCV)

Try other classifiers (Logistic Regression, XGBoost, etc.)

Add feature importance visualization

Deploy the model as a web app using Streamlit or Flask

📝 License
This project is open source and available under the MIT License.

