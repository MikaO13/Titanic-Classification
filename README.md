# Titanic-Classification
Classification of survival of titanic passengers using <a href = "https://www.kaggle.com/competitions/titanic/overview">Kaggle data</a>

Used sklearn, pandas, matplotlib, seaborn

Main code in titanic.ipynb, initial model in titanic_first.ipynb

Light data cleaning to fill missing values

EDA (Exploratory Data Analysis) to understand the dataset, with graphing of some features to visualize what might suggest higher likelihood of survivability

Feature extraction to create/combine initial features into more meaningful features for the purpose of classifying survival 

Feature selection to remove data unhelpful towards solving the classification problem

Building a base RandomForestClassifier to test base accuracy looking at accuracy and cross fold validation accuracy

Hyperparamater tuning 6 models using RandomSearchCV to see how they each performed on this dataset and to have tuned and more useful final models

Ensembled prior tuned models with a StackingClassifier for best performance

