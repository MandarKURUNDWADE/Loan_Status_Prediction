# Loan Status Prediction Using Machine Learning 💰💡

## 📝 Description 
This project aims to predict the loan approval status for applicants using the "loan_prediction.csv" dataset. We will preprocess the data, handle missing values, convert categorical columns, perform feature scaling, and train various classification models. Finally, we will save the best model and create a GUI to predict loan status for new applicants.

## 📊 Dataset 
The dataset used for this project is available in a CSV file named "loan_prediction.csv".

## 🎯 Approach 
1. Display Top 5 Rows of The Dataset.
2. Check Last 5 Rows of The Dataset.
3. Find Shape of Our Dataset (Number of Rows And Number of Columns).
4. Get Information About Our Dataset Like Total Number Rows, Total Number of Columns, Datatypes of Each Column, And Memory Requirement.
5. Check Null Values In The Dataset.
6. Handling The Missing Values: Drop rows with missing values and fill missing values with mode.
7. Handling Categorical Columns: Convert categorical columns to numerical values.
8. Store Feature Matrix In X And Response (Target) In Vector y.
9. Feature Scaling: Scale numerical features to have zero mean and unit variance.
10. Splitting The Dataset Into The Training Set And Test Set & Applying K-Fold Cross Validation: Train multiple classification models and evaluate their performance using cross-validation.
11. Logistic Regression: Train and evaluate a Logistic Regression model.
12. Support Vector Classifier (SVC): Train and evaluate a SVC model.
13. Decision Tree Classifier: Train and evaluate a Decision Tree Classifier model.
14. Random Forest Classifier: Train and evaluate a Random Forest Classifier model.
15. Gradient Boosting Classifier: Train and evaluate a Gradient Boosting Classifier model.
16. Hyperparameter Tuning: Use RandomizedSearchCV to find the best hyperparameters for the models.
17. Save The Model: Save the best model obtained after hyperparameter tuning.
18. GUI: Create a simple GUI using tkinter to take user input and display the loan approval status prediction.

## 📥 Installations 
To run this project, you need to have Python installed on your machine. Additionally, install the required libraries using the following command:
```bash
pip install pandas scikit-learn joblib tkinter
```

## ⚙️ Setup 
1. Clone this repository to your local machine or download the code as a ZIP file.
2. Place the "loan_prediction.csv" file in the same directory as the project code.
3. Open the terminal or command prompt and navigate to the project directory.
4. Run the project code using jupiter notebook
## 🛠️ Requirements 
- Python (>=3.6)
- Pandas (>=1.0.0)
- NumPy (>=1.0.0)
- scikit-learn (>=0.24.0)
- joblib (>=0.14.0)
- tkinter (Standard library)

## 🚀 Technology Used 
- Python
- Pandas
- NumPy
- scikit-learn
- joblib
- tkinter (for GUI)

## ▶️ Run
1. Clone or download the project repository.
2. Place the "loan_prediction.csv" file in the project directory.
3. Install the required libraries using the mentioned command.
4. Run the project code using the specified command in the terminal or command prompt.
5. The GUI window will appear, allowing you to enter applicant details and predict the loan approval status.

---

📝 I frequently create content focused on complete projects in the realm of data science using Python and R.

💬 Feel free to inquire about data science, computer vision, Python, and R.

---

<p align="Right">(◕‿◕) Thank you for exploring my GitHub project repository. 👋</p>
