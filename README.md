#### Sentimental Analysis on Apple and Samsung tweets

In tech, Apple vs Samsung is one of the biggest battle. We are aiming to do a competitive analysis between iphone and samsung smartphones through sentiment analysis from tweets. The battle between Apple's OS and Android always prevails. There is a section of people who wants to use nothing except apple unlike the section of people who do not want to be in Apple's ecosystem. We are scraping tweets from @SamsungNewsUS and @iPhone_News to compare the sentiments associated with them. It is an interesting topic to compare and understand the sentiments across these products. With the increasing popularity of these products expanding each day, this competitive analysis will help understand the market share of each product.

Apple takes first place for smartphones: 43 percent of US consumers reported purchasing Apple branded smartphones in the last year vs 29 percent purchasing Samsung (Source: TraQline, 4QE June 2021. However the global market tells a different story. On the international stage, Samsung ships more smartphones than any other manufacturer, while Apple held second place last quarter. (Source:https://www.traqline.com/newsroom/blog/competitive-analysis-apple-vs-samsung-market-share/)

So this sentiment analysis will help us to understand the emotion weightage across these two brands and will help in assessing the market performance of both the brands. Understanding the performance of these two highly competitive brands will help in many ways. One of the major contribution would be to make decisions on portfolio investment.


##### Process flow:
1. Scaping tweets
2. Cleaning the tweets
3.Apply lemmatization and remove stop words
4.Create target variable use sentiment intensity analyzer( This is assumed to be the original sentiments in this project)
5.Test with different models 
  - Model 1: TF-IDF and Neural networks
  - Model 2: Word embeddings and Neural networks
  - Model 3: Deeplearning model with recurrent and convolution layers (Bidirectional and LSTM layers,SimpleRNN)
6. Analyze the model results
