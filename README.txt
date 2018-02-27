Project for Revanth NLP mentored by Robert Sawyer through STARS (NC State)

TODO List:
3/13	Define Cryptocurrency scope (BitCoin, BitCash, Ethereum, LiteCoin, Ripple, etc)
  3/6		List of cryptocurrencies (name, abbreviations, ticker) -> csv
  3/13		Find data sources on historical prices of cryptocurrencies

	Gather language date regarding Cryptocurrencies
		Sample from Stocktwits by date
			Hashtags

		Sample from Twitter API (Stocktwits?) by date
			Using hashtags from list of crypto?
			Parse streaming data for crypto mentions?

	Use sentiment analysis tool to quantify tweets
		TextBlob? NLTK? Ensemble? Custom?
		Organize by dates leading up to price date
		Compare Stocktwits vs Twitter

	Model the price change as function of sentiment
		Trailing averages leading up to date
		
Useful Sources
Twitter API: https://developer.twitter.com/en/docs/tweets/search/api-reference/get-search-tweets.html
Requests: http://docs.python-requests.org/en/master/
TextBlob: http://textblob.readthedocs.io/en/dev/quickstart.html#sentiment-analysis