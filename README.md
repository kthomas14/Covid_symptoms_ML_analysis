# Introduction to Machine Learning: Analysis of prevelant COVID-19 Symptoms

## Kaylah Thomas

[Link to presentation slides](https://docs.google.com/presentation/d/18mQIuqE_lvfVXbVToCDAJgVsjVvURAGFyf-aD-Nnz3A/edit?usp=sharing)

- Task:
    - summarize your task in less than 3 sentences
      - During the COVID-19 pandemic, there have been many questions about what symptoms are associated with the virus. I would like to use machine learning techniques to determine which symptoms are most closely associated with a positive COVID-19 status. 
    - is it classification (binary or multi-class) or regression?
      - This task is a classification task in which each feature has binary outcomes. 
- Data:
  - What's the data size? How do you get training and testing set?
    - Used train_test_split with 30% testing sample
  - What's your feature space? How many features? What type of features? (e.g., 10 features in total, 8 numerical, 2 categorical)
    - All features are categorical with binary attributes. There are 20 different features leading to the binary classification of whether the sample has a COVID-19 diagnosis. 
  - What data preprocessing steps you have done?
    - Used Ordinal encoder to change the categorical variables to numerical values for easier visualization or the feature space. 
- Model:
  - Which model(s) did you use?
    - Decision tree classifier
  - For each model, which parameter values did you tune (if you are not using the default value)?
    - Entropy
