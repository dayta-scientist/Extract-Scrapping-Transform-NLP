As a **Data Scientist**, the objective of this project is to use **advanced programming techniques** in Python language to extract information from an Argentine economic-financial newspaper called Ambito (https : //www.ambito.com/ ), by using **web scrapping** with the css selector technique. Then, in a second stage called transformation, the necessary cleaning is carried out on the file to finally, in a third and final stage, develop **sentiment analysis**, which is one of the many techniques that can be used to perform within the branch of Data Science called: **Natural Language Processing**, making use of the nltk library.

## The architecture of the project is as follows:

### Extract

- config.yaml
- common.py
- news_page_objects.py
- main.py

>In this first stage, the data extraction is carried out with web scrapping, using the css selector technique, structuring it as follows:

1. URL of each article
2. Title
3. Body


### Transform

- main.py

>In this second stage, we take the .csv file generated in the first stage of **Extract** and carry out all the necessary steps to obtain a clean file that meets the initial requirements.


### Sentiment Analysis

- Analysis.py
- Sentiment_analysis.csv (generated from Analysis.py)
>In this third stage, we use tools provided by the nltk library:

1. Word clouds for the titles and the body of the articles
2. Analysis of words with positive, negative and neutral connotations


# Conclusion:

The initial goal was more than achieved. The use of advanced python techniques for Data Science, obtaining information from the web in a digital diary to meet the requirements of a professional analysis using natural language processing tools and generating a final file called Sentiment_analysis.csv
