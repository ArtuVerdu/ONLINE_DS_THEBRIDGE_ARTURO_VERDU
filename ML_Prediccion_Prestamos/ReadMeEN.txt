Problem Statement:

Our client is a bank that wants AI to predict if a cliente profile is adequate for a loan, based on their desired home location, social, familiar and financial situation.

Used Dataset:

Public Origin Dataset, License CC0 (Public Domain), no copyright of any kind.

Home Loan Approval - Rushikesh Konapure
https://www.kaggle.com/datasets/rishikeshkonapure/home-loan-approval/data

Adopted Solution:

The models used for this were; Logistic Regression, KNN, SVM and Random Forest, but the best results came from the models made from SVM and Logistic Regression.

Repo Structure:

Utilized Technologies:

Libraries used:
Pandas
Matplotlib
Seaborn
NumPy
SKLearn (preprocessing, model_selection, linear_model, neighbors, metrics, svm, ensemble)

Reproduction instructions:

The code can be executed in the order that it is shown, it is viable and recommended to use "Run All Cells" to view.

Main results:

A model with close to 85% accuracy and a F1-Score of 89% has been achieved.

The goal of the model was the highest possible recall for the client (The Bank) to avoid the most False Positives or Bad Approved Profiles at the cost of False Negatives or Good Rejected Profiles.

Author:

Arturo Verdu
- GitHub: https://github.com/ArtuVerdu

