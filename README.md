# Spam Classifier using Email Data from TREC 2007 Public Corpus for classifying emails as Spam / Ham(Not spam) 

1. We will use the files from 'full' folder in this dataset.

2. We will use Pandas to read the content and categorize them into spam:1 and ham:0

3. We will clean up the content by removing line endings , tabs , return characters . We will also remove email addresses, numbers and punctuations from the sentences and convert the text to lowercase.

4. We will use NLTK library to remove stopwords like 'the' 'had' , etc

5. We will will use NLTK for stemming which is to convert various forms of a root word to the root word itself e.g 'like' is the root word for 'liked' , 'likes' , 'liking' , etc . We will use NLTK SnowballStemmer which handles languages other than English. When handling English language alone Porter stemmer could be used.

6. We will use TfidfVectorizer from Scikit Learn library to vectorize and create the train, validation samples

7. We will train and test spam / ham classification using Support Vector Machines and NaiveBayes
