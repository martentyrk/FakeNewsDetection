# FakeNewsDetection
Project members:

Marten Türk
Markus Herman Tiik
Siim Langel

## Data cleaning
All the possible date time stamps throughout all the datasets were formatted into one equal. Unnecessary rows were removed from fake and real news dataset articles. We also formatted the text so that it would not contain any punctuation	or capital letters and etc. We also spilt the second dataset, where the articles were mixed up, into two separate datasets.


## Finding the most popular words
At first we joined the fake news and mix_fake news datasets together, after that the real news and mix_real news datasets together. After that we made two strings: we added fake news texts to one string and real news texts to another. We removed the stop words from strings and then found the top 10 most common words from both strings. Finally we made two bar plots that illustrated the results.
