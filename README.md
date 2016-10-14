# spark-streaming-topic-model
Latent Dirichlet Allocation (LDA) based topic modeling of news corpus in Apache Spark Streaming

# System Requirements

# How it works
![spark-stream-lda](https://cloud.githubusercontent.com/assets/9861437/19377220/fd0d83b4-9201-11e6-96b2-759b04dd0409.png)

# Dataset Download
AG is a collection of more than 1 million news articles. News articles have been gathered from more than 2000  news sources by ComeToMyHead in more than 1 year of activity. ComeToMyHead is an academic news search engine which has been running since July, 2004. 

The dataset is provided by the academic comunity for research purposes in data mining (clustering, classification, etc), information retrieval (ranking, search, etc), xml, data compression, data streaming, and any other non - commercial activity.

The code will automatically download the yahoo news corpus [**Ref**](https://www.di.unipi.it/~gulli/AG_corpus_of_news_articles.html) . In case of some issue, you can directly download the news corpus file (118 MB) from [**here**](https://www.di.unipi.it/~gulli/newsSpace.bz2)

# Core LDA model
<img src="https://cloud.githubusercontent.com/assets/9861437/19376470/b4ee8a48-91fb-11e6-87c6-30c36a4e485e.jpg" height="50%" width="50%"/>

# Online LDA with minibatch processing in Apache Spark
<img src="https://cloud.githubusercontent.com/assets/9861437/19376476/bba1fd5c-91fb-11e6-8bfd-8b826b4298d8.png" height="50%" width="50%"/>

# REF
- http://www.slideshare.net/AlexMinnaar1/vstextbythebay
- http://spark.apache.org/docs/latest/mllib-clustering.html
