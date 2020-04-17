# AutoTaggingStackOverFlowData

- MultiClass, Multi Label Classification problem
- Dataset Contains StackOverFlow Data with Question Title, question and the labels
- Steps:
  - Clean the Data
  - Combine Title and Question into a single column and use Tfidf Vectoriser for creating training set
  - Use Sklearn preprocessing MultiLabel Binariser on the target variable to make it into a Classification problem
  - Build model 1 with Logistic Regression and SkLearn Multiclass OnevsRestClassifier
  - Use F1 Score metric for evaluation
  - Build model with deep learning
  - Create a inference Function to test for new data
  
