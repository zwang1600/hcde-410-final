Zuo Wang
HCDE 410
Dr. Craft
05/16/2021
                                                    **Preliminary Proposal**
**Motivation**
I am planning on doing analysis on the US stock market, with a focus on the S&P 500 index. There are tons of factors that I can analyze with the market data, so I’ve decided to focus on one thing -- the major market crash in recent years. Specifically, two of the big crashes I want to focus on are the 2020 stock market crash (https://en.wikipedia.org/wiki/2020_stock_market_crash) and the financial crisis in 2007-2008 (https://en.wikipedia.org/wiki/Financial_crisis_of_2007%E2%80%932008.) 

By looking at the historic data, I want to gain more insights on how the “big dips” in overall market trend have affected the price of each individual stock, and how each financial sector has responded to the crashes (e.x. whether technology stocks responded differently than the energy stocks in 2008.) 

Being an amature investor, I do hope to learn more about the stock market in general, especially when the market isn’t performing well. Hopefully after conducting this research, I can make more informed decisions in the near future. 


**Dataset**
I am planning on using some of the datasets provided by kaggle, an online platform partnered with Google: 
1. https://www.kaggle.com/paytonfisher/sp-500-companies-with-financial-information
    This dataset contains the financial information for each company included in the S&P 500 index. I will mainly use the “sector” column to identify the category each stock belongs to (e.g. health care, information/technology.)
2. https://www.kaggle.com/paultimothymooney/stock-market-data
    This dataset contains not only the S&P 500 index data but also each individual stock data. This dataset is from 1999 to basically nowadays.


**Unknowns and Dependencies**
These are the dataset I am planning to use for now, but I might use extra sources later in the future. Again, these datasets are provided by individual data scientists on Kaggle platform, and they contain financial metrics that many professionals use in order to evaluate a company. Specifically, the first dataset is provided by the website called datahub (https://datahub.io/core/s-and-p-500-companies-financials/r/1.html.) 

The terms of use on Kaggle can be found here: https://www.kaggle.com/terms
And the privacy policies can be found here: https://www.kaggle.com/privacy

In terms of unknowns, I am not sure if I am fully capable of interpreting the data in a way that’s efficient and useful. Because there are so many metrics in the stock market and I am not expert in this very field, I might just be scratching the surface when it comes to analysis. Other than that, I don’t have any concerns.


**Research Questions**
What were the impacts major stock market crashes had on individual stocks’ prices?
How did each sector respond to the major stock market crashes?


**Background / Related Work**
Overall, the market indices are made up by individual stocks. Specifically, the S&P 500 index is just a weighted measurement of the 500 of the largest companies in the US. Because it is the stock market, nothing is 100% certain, otherwise everyone would be making money. So whether or not there is a correlation between index and its individual stock price can only be determined based on our own interpretation. 

However, there are prior studies done on the topics of stock price synchronicity (similar pattern between index and stock prices.) For instance, in the paper titled The Index and Stock Price Synchronicity: Evidence from Taiwan (https://www.e3s-conferences.org/articles/e3sconf/pdf/2020/58/e3sconf_isceg2020_04029.pdf,) it is hinted that there is no clear answer to the question whether there is a synchronization between stock price and the index.


**Methodology**
First I need to find the period of time in which the market crashed. I will most likely pinpoint the time frames by researching online instead of analyzing the index myself. For example, Wikipedia suggests that the S&P 500 index dropped 34% from February 19 to March 23 (https://en.wikipedia.org/wiki/List_of_stock_market_crashes_and_bear_markets) and I would be using these dates. 

After pinpoint the time frame, I need to look at each individual stock data within that time period. For instance, I would look at Apple’s stock price between February 19 and March 23 and see its trend in terms of stock price. And then I need some metrics (e.g. the percentage of price drop, the shape of the price graph) to compare the index trend and the individual stock trend. And to present the findings, I will have to most likely use a line graph to compare the trends. \

While it is possible to do analysis on each 500 stocks, it would result in too much information to present. Therefore, I would pick a few stocks from each financial sector (e.g. Apple and Microsoft for Information/Technology, Exxon and Kinder Morgan for energy.) and make the representatives for their own sector. 

I would also analyze the trend of each sector to the general index trend. And I would be doing this by gathering the information I produced before on each individual stock and categorizing them according to their sector labels. I would also compare the trend in between sectors to see, for instance, if the price of technology stocks are more heavily affected than the energy stocks. I would present the findings using perhaps a bar chart or a line graph.