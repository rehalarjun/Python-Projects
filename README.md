# 🍔 Python Projects

This repository contains the Python Projects that showcase my Python skills and grasp on Python concepts. 

## 📚 Table of Contents
- [Super Store Analysis](#super-store-analysis)
- [Exploring the NYC Airbnb Market](#exploring-the-nyc-airbnb-market)
- [Statistical and Predictive Modeling for Analytics](#Statistical-and-Predictive-Modeling-for-Analytics)





***

## Super Store Analysis


![image](https://user-images.githubusercontent.com/81607668/127727120-a11f32fa-3042-4773-b54e-fd1a792fff2f.png)
[Image credit](https://www.blogto.com/real-estate-toronto/2021/04/iconic-kims-convenience-store-for-sale-toronto/)

#### Background
Super Store is a small retail business located in the United States. They sell Furniture, Office Supplies and Technology products and their customers are the mass Consumer, Corporate and Home Offices. The data set contains sales, profit and geographical information of individual orders.

#### Business Task
Analyse sales data and determine weak areas and opportunities to boost business growth.

#### Business Questions
- Which Category is Best Selling and Most Profitable?
- What are the Best Selling and Most Profitable Sub-Category?
- Which is the Top Selling Sub-Category?
- Which Customer Segment is Most Profitable?
- Which is the Preferred Ship Mode?
- Which Region is the Most Profitable?
- Which City has the Highest Number of Sales?

#### Tools
Python for Data Cleaning, Data Transformation, Data Visualisation and Data Analysis

#### Data Set
The data set is publicly available on [Kaggle](https://www.kaggle.com/akashkothare/tsf-datasets).





## Exploring the NYC Airbnb Market


#### Background
New York City skyline
Welcome to New York City (NYC), one of the most-visited cities in the world. As a result, there are many Airbnb listings to meet the high demand for temporary lodging for anywhere between a few nights to many months. In this notebook, we will take a look at the NYC Airbnb market by combining data from multiple file types like .csv, .tsv, and .xlsx.

#### Business Task
Analyse sales data and determine weak areas and opportunities to boost business growth.

#### Business Questions
- What is the average price, per night, of an Airbnb listing in NYC?
- How does the average price of an Airbnb listing, per month, compare to the private rental market?
- How many adverts are for private rooms?
- How do Airbnb listing prices compare across the five NYC boroughs?

- What is the average price, per night, of an Airbnb listing in NYC?
- How does the average price of an Airbnb listing, per month, compare to the private rental market?
- How many adverts are for private rooms?
- How do Airbnb listing prices compare across the five NYC boroughs?


#### Tools
Python for Data Cleaning, Data Transformation, Data Visualisation and Data Analysis


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


