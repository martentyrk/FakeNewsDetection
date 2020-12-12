This is a description of each dataset in this folder.

https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset
From this link we got the fake.csv and true.csv
Both datasets have been cleaned from nan values and the date has been formatted to the same format for every dataset.

https://www.kaggle.com/ruchi798/source-based-news-classification
From this link we got the mix_fake, mix_true,
mix_true_with_stop and mix_fake_with_stop.

Each dataset has been cleaned of nan values and the date has been formatted to the same format for every dataset.

Because we were given the title and text without the stopwords, I created two separate datasets
which have the columns ['title without stopwords', 'text without stopwords', 'date']

Each dataset has 3 columns, so they can easily be merged together if needed.