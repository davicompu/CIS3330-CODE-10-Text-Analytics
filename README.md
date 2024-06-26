## CIS3330-CODE-10-Text-Analytics

## Instructions

Text analysis allows the quantification of information from textual datasets. In this CODE assignment, you are asked to perform your first text analysis using data from Amazon customer reviews. In this CODE assignment, you must choose **one category** of customer reviews and provide initial insights about customer reviews that are discussed under the **text** column.

## Deliverables

In a Word or PDF, deliver a report of your analysis. Your report must include the following sections.

1. Descriptive analytics report
  *  Describe the dataset you chose in terms of:  
        a. Ratings (1-5 stars)  
        b. Text length  
        c. Text adjectives  
        d. Text nouns  
        e. Text sentiment  
2. Text insights report
  * Report 1-2 insights that you obtained from conducting your descriptive analytics report.
  * Report a recommendation that you will advise a customer when deciding about a product you analyzed.
  
You need to submit the report in Blackboard and in your code repository. Finally, **do not forget** to submit all the code you developed for your analysis, and anyone will need to replicate your work in the code repository.

## Useful Python code

* Tokenization and part of speech (POS)  
`for review in reviews: `   
`    tokens = nltk.word_tokenize(review) # tokenization`  
`    pos_tags = nltk.pos_tag(tokens) # part of speech`  

* Sentiment analysis with VADER  
`from vaderSentiment.vaderSentiment import SentimentIntensityAnalyzer`  
`analyzer = SentimentIntensityAnalyzer()`  

## Useful resources

* Valence Aware Dictionary and sEntiment Reasoner - https://github.com/cjhutto/vaderSentiment
* Natural Language Toolkit - https://www.nltk.org/

## Data disclosure

The data is licensed under public domain (CC0 1.0) and was obtained from the Harvard Dataverse - https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/W96OFO
