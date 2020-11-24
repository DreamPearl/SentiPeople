# SentiPeople
This application analyses the public data available on Twitter to get people’s sentiment on the given firm in order to enhance the customer experience of the given firm.
Steps involved in this:
1. Fetching twitter tweets regarding the firm through twitter API’s and then stores necessary information in MongoDB.
2. The Sentiment Analyzer fetch the stored data from MongoDB and then use Natural Language Processing on each tweet to determine whether it’s showing positive, negative or neutral sentiment.
3. In addition, based on the computed information, the application visualizes the data into multiple graphs using matplotlib. This help us to understand the trust of the customers on the company over the span of time. 
