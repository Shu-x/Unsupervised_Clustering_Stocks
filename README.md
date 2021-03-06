# Unsupervised Clustering of Stocks
Associative movements in stock prices are referred to as **sympathy plays**, which typically occur when a company’s stock is indirectly affected by another company’s stock or news. Sympathy plays may drive another stock, a group of stocks, or possibly an entire sector in a particular direction as their trades gain momentum.

This research will explore **unsupervised clustering methods to group stocks in the medical specialties and pharmaceutical industries listed on NASDAQ** that exhibit similar patterns in hourly price movement as an empirical measure. The clusters may help day traders to narrow down stocks in a watchlist for a sympathy play strategy, or provide indication of similar stocks to avoid in a diversification strategy.

The following methods were applied on hourly stock price data from Yahoo! Finance
1. KMeans clustering
2. Agglomerative clustering
3. Spectral clustering
4. Gaussian Mixture Model

However, results did not yield strong conclusive evidence of distinct clusters, suggesting that hourly price movement alone was an insufficient metric for identifying clusters that persist over a few months.
