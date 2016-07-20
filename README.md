# Hypothesis Testing: Data Automation for Civic Graph

## In this repo...
* Testing different NLP tools (spaCy, nltk and others) to analyze corpus of blog content about civic tech
* Algorithm for discerning high level information about folks in the civic technology scene
...Sentence tokenization of training data
...Categorize training data as having or not having a particular label (funding, data, employment, collaboration, location) 
...Create classifier for each label using a Support Vector Machine

## To do:
* Run each classifier on test data
* Parse sentences once labels have been defined to do Named Entity Recognition (NER) and use the correct action words to imply causality (on training? on test?)
* Save results to database (create new schema or pipe directly to Civic Graph)?
* Design pipeline to Civic Graph backend
