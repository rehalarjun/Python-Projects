## Statistical and Predictive Modeling for Analytics


### Background

Mr. John Hughes has been reviewing the `wireless_churn.csv` dataset and seeks to develop three forecasting models using Logistical Regression, Naïve Bayes, and Voting Ensemble to predict customer churn.

### Dataset Description
The dataset contains 3,333 observations and 11 variables, including various customer metrics and a churn indicator.

#### Independent Variables
- **AccountWeeks**: Number of weeks the customer has had an active account.
- **ContractRenewal**: 1 if the customer recently renewed the contract, 0 if not.
- **DataPlan**: 1 if the customer has a data plan, 0 if not.
- **DataUsage**: Gigabytes of monthly data usage.
- **CustServCalls**: Number of calls to customer service.
- **DayMins**: Average daytime minutes per month.
- **DayCalls**: Average number of daytime calls.
- **MonthlyCharge**: Average monthly bill.
- **OverageFee**: Largest overage fee in the last 12 months.
- **RoamMins**: Average roaming minutes per month.

#### Dependent Variable
- **Churn**: 1 if the customer cancelled service, 0 if not.

## The Ask

Using Python and Jupyter Notebook, create a comprehensive script that includes the following steps:

1. **Exploratory Data Analysis (EDA)**
   - Conduct EDA using `pandas-profiling` to uncover key insights.

2. **Remove Anomalies**
   - Remove outliers using the Isolation Forest technique.

3. **Create Learning Curves**
   - Generate learning curves for both Logistical Regression and Naïve Bayes models, using recall for scoring (`scoring='recall_weighted'`).

4. **Optimize Models**
   - Develop optimized models (including ROC/AUC curves) for:
     - Logistical Regression
     - Naïve Bayes

5. **Ensemble Voting Model**
   - Create an ensemble voting model to predict the proper classification. The ensemble should include:
     - One algorithm (Logistical Regression or Naïve Bayes)
     - One Bagging or Boosting technique (Bagging, Adaboost, or Gradient Boosting)

6. **Next Steps**
   - Identify one algorithm (Logistical Regression, Naïve Bayes, or Voting Ensemble) to be implemented by Mr. John Hughes.
   - Propose and justify two next steps to enhance the usability of the selected model.

## Tools

- Python
- Jupyter Notebook
- `pandas-profiling` for EDA
- `sklearn` for machine learning models and outlier detection

## Data Set

The dataset used in this project is `wireless_churn.csv`, containing customer data related to account activity and service usage.

## Project Workflow

1. **Exploratory Data Analysis**
   - Utilize `pandas-profiling` for a comprehensive EDA.
   
2. **Anomaly Detection and Removal**
   - Implement Isolation Forest to detect and remove outliers.

3. **Learning Curves**
   - Plot learning curves for Logistical Regression and Naïve Bayes models.

4. **Model Optimization**
   - Optimize models and generate ROC/AUC curves.

5. **Ensemble Model**
   - Develop and evaluate an ensemble voting model.

6. **Model Selection and Future Steps**
   - Select the best model and recommend next steps for improvement.

## Next Steps

1. **Model Deployment**
   - Implement the chosen model (Logistical Regression, Naïve Bayes, or Voting Ensemble) in a production environment.

2. **Model Enhancement**
   - Explore additional features or alternate data sources to improve model accuracy.
   - Consider advanced machine learning techniques such as deep learning or other ensemble methods for future iterations.

## Deliverables

1. **PowerPoint Presentation**
   - A PowerPoint deck (PPT or PPTX) reporting analysis, findings, and conclusions. Ensure all key facts are included in the slides.

2. **Jupyter Notebook**
   - Python code presented in a Jupyter Notebook, exported as .html.
