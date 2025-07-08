# TwitterSentimentAnalysis
Twitter Data Sentiment Analysis for NASDAQ Companies using Apache Spark

Today, sentiment analysis is a vital tool to understand public opinion and market sentiment, especially in the financial markets. Through sentiment analysis done on social media, investors and market analysts have the opportunity to gain information about market trends and sentiment expressed by investors. X (formerly Twitter) with its vast user base and real-time nature information flow, has become a prominent platform for sharing opinions and news and thus, increasing the scope in leveraging this data source for sentiment data collection and gaining insights especially in the financial markets. This work focuses on sentiment analysis for the NASDAQ-listed company posts on Twitter, aiming to use the large and dynamic data in the social media world in order to get public perception on companies and thereby make informed predictions on the market. It involves the preprocessing of the Twitter data gathered, the preprocessing of labeled data by cleaning and tokenizing, and the labeling of the remaining data by the VADER sentiment analysis tool.
### Dataset from Kaggle [![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/omermetinn/tweets-about-the-top-companies-from-2015-to-2020)
 

![image](https://github.com/user-attachments/assets/8e65615f-4f23-4b8e-be80-efc2d87b5b53)
Fig. System Design of the Proposed Framework

Apache Spark's distributed computing capabilities allowed for handling large volumes of data and performing computations in parallel, leading to faster processing times and improved scalability.
Various classifiers, including Random Forest, Decision Tree, MLPC, and Logistic Regression, were employed to provide valuable insights into sentiment classification accuracy and performance.
Among the classifiers for sentiment classification, the results showed that the Logistic Regression classifier performed reasonably well for the majority class (Neutral and Positive sentiments) of the huge amount of tweet data, but struggled with the Negative sentiment class, paving the way for more exploration and highlighting the potential of social media sentiment analysis in providing valuable insights for market analysis and investment strategies.
