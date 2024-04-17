# Salifort Motors (Capstone Project)

As part of Google's Advanced Data Analytics Certificate program, 
I completed a capstone project that involved performing Exploratory Data Analysis (EDA), creating data visualizations, 
creating a machine learning model, deriving insights from it, and preparing an executive summary document.

To complete this project, I was given templates to make an executive summary, a dataset available publicly on 
[kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv), 
a strategy document, and a jupyter notebook outlining the steps I would take to complete the project and questions that I should consider. 
The important questions are answered in the executive summary or below.

The business scenario for this project involved performing data analysis for the HR department of the fictional consulting firm "Salifort Motors". 
The goal of this project is to answer the question "what is likely to make employees leave the company?" 
We are asked to determine an answer to this question by analyzing the data provided by the HR department (public domain on kaggle)
and build a machine learning model that can predict if an employee will leave or not. 
We were given a choice as to what kind of model we could use. I used an XGBoost model.

### Deliverables:
- The completed jupyter notebook
- An executive summary
- The model that was built

### Ethical Considerations:
Throughout the project, we are asked to consider if there are any ethical concerns.

One of the main concerns is that we are building a model that will be used to make decisions that will impact employees.
While the goal is to decrease employee turnover, we need to always take into consideration how 
decisions made based on the model's results will impact employees. Ideally this would be discussed during the planning stage of the project.

Another concern is why we are being asked to build a model that predicts if an employee will leave rather than predict satisfaction.
If the company cares more about employee satisfaction than turnover, 
then building a model that predicts satisfaction may lead to more direct decision-making. 
Ideally, this discussion would also take place during the planning stage.

Since all the data collected is from the same company, any model created using it will suffer from overfitting and will
not perform as well when used on data from outside the company. This will not be an issue for our purposes, however, 
it is worth keeping in mind that the accuracy of the model will not be consistent if used in a different environment.


### Required Packages:
- jupyter
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost


### Useful Links:

- [pandas API reference](https://pandas.pydata.org/docs/reference/index.html)
- [seaborn API reference](https://seaborn.pydata.org/api.html)
- [scikit-learn API reference](https://scikit-learn.org/stable/modules/classes.html)
- [XGBoost Classifier](https://xgboost.readthedocs.io/en/stable/python/python_api.html#xgboost.XGBClassifier)
- [HR Analytics Job Prediction Dataset (CC0: Public Domain License)](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv)
