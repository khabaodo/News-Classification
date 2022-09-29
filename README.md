# Purpose
In this project, I want to build a machine learning model to classify fake news and real news

# Results
The model has an accuracy score of 94.63%

# NLP Techniques Used
- Built custom text-processing function to remove punctuation and stopwords from the text file. This function removes uncessary characters and words in the text, which could hinder the model's performance
- Utilized sklearn's CountVectorizer to tokenize the text
- Implemented sklearn's TfidfTransformer to create a matrix of TF-IDF features.
- Used sklearn's pipeline to quickly transform the models for machine learning.
- Used Passive Aggressive Classifer model to train the data
