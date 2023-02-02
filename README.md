# Twitter Sentiment Analysis
This code uses the Twitter API and OpenAI to analyze the sentiment of Bitcoin tweets. The sentiment of each tweet is determined using OpenAI's Completion API and the results are displayed in a pie chart, showing the percentage of tweets that are positive, negative, or undetermined.

## Requirements
tweepy,
openai,
matplotlib,
python-dotenv


## Usage
1. Create a .env file and store your Twitter API credentials and OpenAI API key.

2. Run the script using `python sentiment.py`. The pie chart will be displayed.

## Note: 
You can adjust the number of tweets retrieved by changing the value of count in the function `api.search_tweets(q="Bitcoin", lang="en", count=10)`. I have kept it deliberately low given the OpenAI API cost, but you could easily change this to 10,000 or 50,000 tweets for example. You can also change the search word here to include other search terms such as 'BTC' or even a search term completely unrelated to Bitcoin.

## Important
In order to capture tweets you will need elevated Twitter API access. You will need to apply via your Twitter developer console.