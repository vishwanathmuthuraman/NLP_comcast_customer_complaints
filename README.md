# Consumer complaints topic extraction using Latent diriclect allocation (LDA) and Latent semantic analysis (LSA)

LSA is a method of analyzing text data using principal component analysis. LDA is a probabilistic approach, utilizing the Dirichlet distribution. Over-fitting is less likely with LDA since it uses priors.
Additionally, both documents and words are represented by orthogonal vectors. LDA is concerned with independent topics, while LSA is concerned with orthogonal representations.
Lastly, LDA requires a minimum number of topics or components. K is selected as the most effective method for capturing the majority of variations in the data.

![alt text](https://github.com/vishwanathmuthuraman/NLP_comcast_customer_complaints/blob/main/Topic-Modeling-using-LSA-NMF-and-LDA-After-topic-modeling-we-identify-topic-topics.jpg)

# Comcast consumer complaint dataset

This dataset was obtained from kaggle and made readily available to all by charlie.H. This data set contains 2 CSV files.
comcast_consumeraffairs_complaints.csv
comcast_fcc_complaints_2015.csv
The first data set however is more beneficial for sentiment analysis. We will be working with the second dataset today comcast_fcc_complaints_2015.csv. it contains several columns including one with verbatim which we will use for topic extraction.
