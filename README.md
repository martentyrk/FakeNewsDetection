# FakeNewsDetection
Project members:

Marten Türk
Markus Herman Tiik
Siim Langel

## How to run it.
In order to run the code you must download Jupyter Notebook. That can be easily done using the Anaconda Navigator. Once downloaded, open the CleanData notebook first, click "Kernel"-> Restart and Run all. That will download the cleaned datasets for you.
Now open the NewsDetection notebook and Restart and Run all again. This notebook will train the models and you'll end up with 4 different models with a 4-article test in the very end, that will display results with a completely random article.


## Data cleaning
All the possible date time stamps throughout all the datasets were formatted into one equal. Unnecessary rows were removed from fake and real news dataset articles. We also formatted the text so that it would not contain any punctuation	or capital letters and etc. We also spilt the second dataset, where the articles were mixed up, into two separate datasets.


## Finding the most popular words
At first we joined the fake news and mix_fake news datasets together, after that the real news and mix_real news datasets together. After that we made two strings: we added fake news texts to one string and real news texts to another. We removed the stop words from strings and then found the top 10 most common words from both strings. Finally we made two bar plots that illustrated the results.

## Models
We used 4 different models: Random Tree, Decision Tree, Logistic Regression and Multinomial NB(Naive Bayes)
Before training the models, we used TfidfVectorizer to remove the stop words from the articles and then transform the articles into vectors. That is because we can't give the models words to train with but numbers and vectors do a good job at that. 

With the given dataset our prediction accuracies were the following:

LogisticRegression accuracy: 0.97

DecisionTreeClassifier accuracy: 0.98

RandomForestClassifier accuracy: 0.94

MultinomialNB accuracy: 0.92

One of our goals was to get a model that could predict articles with a percentage of over 93% and as we can see we accomplished that with 3 models instead of just one.
