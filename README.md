# Regression
The goal of this project is to develop machine learning (ML) models for a regression task. I trained two ML models for regression and explored the impact
of different hyperparameter values on the error achieved by your models. I also prepared a short .pdf report discussing my findings.

A dataset called steel.csv can be seen in this repository. This dataset has been split into separate training and test sets in the Jupyter Notebook. The data is supplied in comma separated values format. Each row describes one instance in the dataset. The attributes are in columns in the following order: normalising_temperature, tempering_temperature, percent_silicon, percent_chromium, percent_copper, percent_nickel, percent_sulphur, percent_carbon, percent_manganese, tensile_strength. The goal of the regression models is to predict the value of the target attribute tensile_strength.

I selected two regression algorithms from the scikit-learn package, and then apply them to this dataset to train predictive models.

A list of available scikit-learn regression implementations can be found at: https://scikit-learn.org/stable/supervised_learning.html 

The models were trained and evaluated using 10-fold cross validation on the supplied dataset. I choose one domain independent and one domain specific measure of error to evaluate my trained models. I reported average training and test set results over all folds for each model. I presented the average results for each model using the default hyperparameter settings in scikit-learn, and results achieved when attempting to tune two of the available hyperparameters for each model. For each model, I choose any two available hyperparameters to tune. 
