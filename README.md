The aim of this project is to detect whether a website is spam or ham. this notebook is to give an idea of how modern phishing website attacks can be prevented using machine learning. To do this, we are going to use the Phishing Websites' Dataset. The viewers are requested to take a look at this dataset. The paper of dataset discusses the data generation strategy in details and how the authors were able to come up with the most significant set of features for detecting phishing websites.

There are 30 features along with the separate target variable and has 11055 samples.

The accuracies achieved is
1) Logistic Regression = 90.99
2) RandomizedSearchCV = 91.27
3) Decision tree = 91.5
4) Knn classifier = 86.4
5) random forest= 94
6) Neaural network = 86.6


There is a script implemented to featurize the url and test it againt different models.
