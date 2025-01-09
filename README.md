# Employee Attrition Prediction and Insights

## Description
This project predicts employee attrition using various machine learning models, including Logistic Regression, Decision Trees, Random Forests, and Neural Networks. It identifies key factors influencing attrition and provides actionable insights to HR professionals to enhance employee retention.

## Files
- **Data_Science_Project.ipynb**: Jupyter Notebook containing the data analysis, modeling, and visualization.
- **WA_Fn-UseC_-HR-Employee-Attrition.csv**: Dataset used for training and testing the models.
- **Attrition_Analysis_Report.pdf**: Summary of findings and recommendations.

## Dataset Details
- **Source**: [IBM Watson HR Analytics Employee Attrition Dataset](https://www.ibm.com/communities/analytics/watson-analytics-blog/hr-employee-attrition/)
- **Features**:
  - `Age`: Age of the employee.
  - `Attrition`: Target variable (Yes/No).
  - `BusinessTravel`, `Department`, `JobRole`: Categorical variables related to employee roles and movement.
  - `MonthlyIncome`: Numeric variable for employee salary.
  - `OverTime`: Indicator if the employee works overtime (Yes/No).
- **Target**: Predicting `Attrition`.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn

## How to Use
1. Clone this repository: `git clone https://github.com/sakibek/employee-attrition-prediction.git`
2. Open the Jupyter Notebook `Data_Science_Project.ipynb`.
3. Follow the notebook steps to preprocess the data, train models, and visualize insights.

## Key Insights
- **Attrition Drivers**:
  - Employees working overtime have a significantly higher attrition rate.
  - Monthly income and total working years are strong predictors of retention.
- **Model Performance**:
  - Logistic Regression and Neural Networks performed the best with test accuracies of 85%.
  - Random Forests and Decision Trees also provided valuable insights into feature importance.

## Contact
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/sakibek) for questions or collaboration opportunities.
