# covid-fake-news-detection-
 
Data Collection: 
Web scraping from PolitiFact to gather COVID-19-related news articles and claims. 
Utilizing the "Fighting an Infodemic: COVID-19 Fake News Dataset," which includes 10,700 
manually annotated social media posts and articles labeled as real or fake news. 

• Data Preparation: 
Data cleaning: Removing HTML content, punctuation marks, special characters, URLs, 
hashtags, mentions, and performing lemmatization. 
Exploratory Data Analysis (EDA): Analyzing the dataset to understand the distribution and 
characteristics of fake news. 

• Data Merging: 
Combining the web-scraped dataset with the "Fighting an Infodemic" dataset to create a 
comprehensive dataset for modeling. 

Vectorization: 
Applying three different vectorization techniques: Word2Vec, end-to-end embeddings with 
CNN, and BERT embeddings. 

• Modeling: 
 Developing and training various models: CNN with end-to-end embeddings, CNN 
with Word2Vec, LSTM, BERT, and RoBERTa. 
