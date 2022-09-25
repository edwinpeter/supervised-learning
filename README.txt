Pre-req: Python environment with packages

scikit-learn           1.1.2
seaborn                0.12.0
pandas                 1.2.3
numpy                  1.19.5


0) Download files from https://archive.ics.uci.edu/ml/datasets/spambase and https://archive.ics.uci.edu/ml/datasets/bank+marketing and put the folders here. 
You should have bank-additional folder and spambase folder here.

1) Run eda_bank_marketing.ipynb to generate the file: bank-additional-clean.csv
2) Run eda_spambase.ipynb to generate the file: spambase.csv
Note: These 2 folders files have already been included here in this folder, if you want you can skip step 0, 1 and 2 but its stated here for clarity on how I generated these files

3) Run each of the notebooks.

Note: utils.py contains some helper functions that are used in the notebooks.

3a) Decision Trees:
decision_trees_spambase.ipynb
decision_trees_bank_marketing.ipynb

3b) Neural Networks:
nn_spambase.ipynb
nn_bank_marketing.ipynb3c) Boosting:
gradient_boosting_spambase.ipynb
gradient_boosting_bank_marketing.ipynb

3d) SVM:
svm_spambase.ipynb
svm_bank_marketing.ipynb

3e) K nearest neighbours
knn_spambase.ipynbknn_bank_marketing.ipynb