# neuralNetPractice


# Table of Contents 
  - [Overview](#overview)
  - [Resources](#resources)
  - [Data](#data)
  - [Results](#results)
  
  ## Overview
  This project uses machine learning models to predict the success of ventures paid by the made up company "Alphabet Soup". The goal is to create a binary    classifier that is capable of predicting whether or not an applicant will be successful if funded by "Alphabet Soup" using the features collected in the  dataset. The results of this project can be viewed in the notebook titled alphabetsoup.ipynb, or down below. 
  ## Resources
  - jupyter notebook, sklearn, tensorflow, pandas, numpy, vscode
  
  ## Data
   - charity_data.csv, bank_telemarketing.csv, hr_dataset.csv
  ## Results
Two hidden layers were chosen for the deep learning model used on the charity_data.csv. The number of neurons was determined by the length of the X_train_scaled variable. This variable contains the number of features in the dataset. Two neurons had the best results when using the tensorflow playground so thats how many were used for this project. The number of neurons in subsequent attempts was altered using the standard rule of 2-3 times the number of features. The target of 75% accuracy was not achieved. The closest this model was able to come was 74% accuracy. Steps taken to try and increase model performance include altering the number of neurons, and the number of epochs used for testing. The best combination was our original number of hidden layers and neurons with the number of epochs increased from 50 to 100. I would choose a support vector machine (SVM) model to solve this classification problem. We trained a support vector machine on  bank_telemarketing.csv as well as a deep learning model. This dataset is similarly complex to charity_data.csv. The SVM model achieved an accuracy score of 87% and ran in seconds compared to minutes vs the deep learning model. SVM's are great binary classifiers, and the problem we are looking at here is binary classification. 
