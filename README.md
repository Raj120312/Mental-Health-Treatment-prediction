# Mental-Health-Treatment-prediction
Developed a machine learning model which predicts whether a person should undergo medical treatment based on a public Dataset extracted from Kaggle.

It included various parameters / features like Gender, Country, Occupation, Changing habits, etc.
Since it was a classification case , whether a person should undergo medical treatment or not , we used classic go to machine learning algorithms of Logistic Regression , RandomForestClassifier and XGboost .
Out of the three algorithms , XGboost performed the best giving us 75% accuracy.
Further hyperparameter tuning was performed , but there was no drastic change in the accuracy of it.

Next steps :- To perform various feature engineering techniques to make the accuracy reach atleast upto 80%.


Prerequisites -

There are two files attached. One is the dataset with .xlsb extension which is compressed (when the repository gets downloaded , save the file as .csv )and another one is .ipynb file which can be opened with Jupyter notebook application

To have python installed and have jupternotebook application
Install necessary libraries by running following command in jupyter notebook "pip install pandas numpy matplotlib seaborn"
How to run - Clone the repository

git clone https://github.com/Raj120312/Mental-Health-Treatment_prediction.git

cd Mental-Health-Treatment_prediction

Open Jupyter notebook and run all cells to produce the analysis
 
