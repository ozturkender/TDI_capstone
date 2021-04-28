Wireless Telecom Carriers constitutes a massive market with the size of $278.8bn involves around 20K businesses and creates almost 300K jobs, according to Ibisworld [1]. Even though the market size remained steady on average for the last 5 years, introduction of new services those will be enabled with 5G&Beyond/6G and end of the pandemic will boost this market soon.
Customer-management-wise, the major problem of the companies are the high disloyalty rates i.e. high churn rates, of the customers. Latest survey of DBmarketing [2] show that the annual average churn rate varies between 10-67%, which means a company loses up to 67% of its customers at the beginning of the year throughout the year. It is intuitive that acquiring a new customer is more costly in comparison with retaining an existing one.

The aim of this project is to predict the customers that are likely to churn soon based on the usage/billing/device/household and several other data. Some of the key aspects of this project are:
==> Data has 100 features with 100K rows with some null values.
==> Given the fact that marginal cost of a call made or a text message is extremely low, reducing churn rate for high-value customers would require more attention.
==> Correctly predicting churns is more important than missing the non-churns, i.e. avoiding Type II error is more critical with the hypothesis "Customer X will not churn within 31-60 days"
==> Feature engineering will play a critical role for high accuracy predictions as most of the features are raw averages.
==> Target class is almost balanced. i.e. 49.6 - 50.4%

Initial explorations made on the data show that most of the currently ready raw features exhibit resembling behaviors for churn and non-churn customers. Only a few of them have meaningful resolution. A high accuracy on True Negatives will yield to decreased churn rates that has direct impact on company profitability.
