# Project-Hyperlaunch
🚢 Titanic Fare Prediction - Project Overview
📦 Source:

->The Titanic dataset comes from the tragic sinking of the RMS Titanic in 1912.

->o develop a machine learning model using Logistic Regression that predicts whether a passenger survived the Titanic shipwreck based on features such as age, gender, and passenger class.

->It is available in many ML libraries like Seaborn, Kaggle, and Scikit-learn.


 🎯 Purpose:
 
->To predict survival of passengers based on personal and travel details.

->It’s great for learning classification, regression, and data preprocessing.

column	Type	Description:
*survived	Binary (0/1)	Target variable: 1 = Survived, 0 = Did not survive

*pclass	Categorical	Passenger class: 1 = Upper, 2 = Middle, 3 = Lower

*sex	Categorical	Gender of the passenger

*age	Numeric	Age in years

*sibsp	Numeric	# of siblings/spouses aboard

*parch	Numeric	# of parents/children aboard

*fare	Numeric	Ticket fare paid

*embarked	Categorical	Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)


🧠 Common Uses in ML:
->Classification: Predict survived (yes/no)

->Regression: Predict fare, age, etc.

->EDA (Exploratory Data Analysis): Age distribution, survival by class, gender-based survival

->Feature Engineering: Convert categorical data, handle missing values, etc.

🧠 Machine Learning Model:

->Logistic Regression is used as it is suitable for binary classification problems (Survived/Not Survived).

->It predicts the probability of survival based on inputs like age, sex, and class.

🧪 Steps Followed:
1.Load and explore the dataset.

2.Clean the data:

3.Handle missing values

4.Convert categorical values (e.g., sex) into numeric

5.Split data into training and test sets.

6.Train the Logistic Regression model.

7.Evaluate the model using:

8.Accuracy

9.Confusion Matrix



🔎 Dataset Size:

->Rows: ~891 passengers (depending on version)

->columns: ~10 features


🧠 Logistic Regression – Titanic Survival Prediction
✅ Goal:
->Use features like age, sex, and pclass to predict if a passenger survived (1) or not (0).


📈 Output You’ll See:

->Accuracy: Overall model performance

->Confusion Matrix: True/False predictions

->Classification Report:

->Precision: Correct positive predictions

->Recall: Model's ability to find all positives

->F1-score: Balance between precision and recall


✅ Example Use Case:

->Predict whether a 30-year-old female in 2nd class would survive the Titanic.


syedalifathima.N
