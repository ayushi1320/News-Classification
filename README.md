# News-Classification
This project aims at building a model which classifies whether a news is a genuine news or a false news  by using Natural Language Processing
We used datasets: fake.csv and true.csv which contains 4 columns [TITLE, TEXT, SUBJECT, DATE] which can be included or removed based on requirements and number of rows are number of sets we considered like in fake.csv we have 23481 and in true.csv we have 21417 which has different subjects involved like politics, Government news etc.
Supervised Learning is used where we have input variable X and output variable y and we use an algorithm to learn the mapping function from input to output y=f(X). All classifications comes under supervised learning i.e. all category outputs comes under this "THIS PROJECT CLASSIFIES WHETHER THE NEWS IS GENUINE OR NOT".
Natural Language Processing is used which is a branch of Artificial Intelligence that studies how machine understands human language. This project under goes text analytics which is an Artificial Intelligence technology that uses NLP to transform free text in documents and databases into normalized, structured data suitable for analysis or to drive ML algorithm.
NLKT is the main tool used here to preprocess text data for further analysis. Text preprocessing here contains of : TOKENIZATION, STEMMING, STOPWORD REMOVAL.
TOKENIZATION: NLTK provides a function called word_tokenize() for splitting strings into tokens
STEMMING:The idea of removing suffix of the word and reducing different forms of a word to a core root. Here Snowball Stemmer is used.
STOPWORD REMOVAL: A stop word is a commonly used word that a search engine is programmed to ignore.
VECTORIZATION:which is used to convert texual data to numerical format. A matrix is cereated in which each column reppresents a feature and each row represents an individual review.
PASSIVE-AGGRESSIVE CLASSIFICATION is an incremental learning algorithm where its Passive if the prediction is correct, no changes are required and Aggessive if prediction is incorrect , make changes to model.
LOGISTIC REGRESSION: used for the classification problems, it is a predictive analysis algorithm and based on concept of probability.
