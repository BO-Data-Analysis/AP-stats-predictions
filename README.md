# AP Statistics Test Score Predictions
Predicting test scores on the AP Statistics Exam based on a student's exam and quiz scores.
## Data: `Combined-Data-Table.csv`
- 223 Students from Homestead High School taking AP Statistics over the course of 2 years with the same teacher.
- Each student has grades for semester 1 and semester 2 on overall grades (0-100), assignments, exit tickets, FRQs, MCQs, Final exam and AP test score (1, 2, 3, 4, 5)
  -  Some students dropped after first semester.
## Methods:
### Linear Regression:
- Used `LinearRegression` from `sklearn.linear_model`.
- Accuracy: ~ 69.5%
### MLP Regression Model:
- Used `MLPRegressor` from `sklearn.neural_network`.
- Hidden layers: (9,6,3)
- Random state: 673
- Accuracy: ~ 72.3%
### Decision Tree Classifier:
- Used `DecisionTreeClassifier` from `sklearn.tree`.
- Accuracy: ~ 60.2%
### AutoGluon Tabular Predictor:
- Used `TabularPredictor` from `autogluon.tabular`.
- Accuracy: ~ 73.2% (could probably be improved)
