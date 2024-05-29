# Binary Classifiers for Metastatic Cancer 
## This project uses 5 different machine learning model configurations to predict if patients received metastatic cancer diagnosis within 90 days of screening. 

The purpose of this project is to compete in the WiDS Datathon 2024 Challenge #1 hosted on Kaggle. The objective is to use a dataset containing patient information (e.g., age, weight, ethnicity) to determine if the patient has received metastic cancer diagnosis within 90 days of their screening. The dataset, provided by WiDS, was extensively explored and preprocessed before training 5 different supervised machine learning models. These models, implemented for binary classification, include:
* Support Vector Machine
* Logistic Regression
* Random Forest
* Extra Trees
* Stacking Generalization

## How to download and use the jupyter notebook

Here are the steps for setting up and running this notebook.

1. Navigate to preferred directory
   ```
   cd <directory>
   ```
3. Clone the project
   ```
   git clone https://github.com/ouriquco/metastatic-cancer-classifiers.git
   ```
5. Run the first code cell
6. Run the remaining code cells

## How to tweak this project for you own uses

Here are some examples of how the code can be reused in your own project.

1. Adopt most of the logic in the clean_text function for your own NLP tasks
2. Adopt the logic in the balance_and_sample_data function to balance classes for either binary or multiclass classification
3. Adopt pipelining, stacking, and hyper parameter searching techniques in your own implementations

## Find a bug?

If you have found an issue and would like to improve the project, please submit an issue using the issue tab above. If you would like to sumbit a PR with a fix, reference the issue you created. 



