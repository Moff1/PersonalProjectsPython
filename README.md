### This project is showcasing the NLP model, and how it interacts with a dataset in additional data exploration

### Import Packages

### Import Data

### EDA 
Notice the use of the lambda function to extract the year

### NLP Classification

### PipeLine - MultiNomialNB()
This pipeline has three components:
 - CountVectorizer(): Convert a collection of text documents to a matrix of token counts
 - TfidfTransformer(): The goal of using tf-idf instead of the raw frequencies of occurrence of a token in a given document is to scale down the impact of tokens that occur very frequently
- MultiNomialNB(): the model in question

### Pipelie - Logistic Regression
This pipeline has three components:
 - CountVectorizer(): Convert a collection of text documents to a matrix of token counts
 - TfidfTransformer(): The goal of using tf-idf instead of the raw frequencies of occurrence of a token in a given document is to scale down the impact of tokens that occur very frequently
- LogisticRegression(): the model in question

### Pipeline Three - XGBoost
This pipeline has three components:
 - CountVectorizer(): Convert a collection of text documents to a matrix of token counts
 - TfidfTransformer(): The goal of using tf-idf instead of the raw frequencies of occurrence of a token in a given document is to scale down the impact of tokens that occur very frequently
- XBGClassifier(): the model in question

Conclusion: Out of the three pipelines are models, the one that performed the best was the XGBoost model, with Logistic Regression close behind. Maybe with some parameter tuning the MultiNomial model could catch up in accuracy to the other two, but for now it remains the worse model. 
