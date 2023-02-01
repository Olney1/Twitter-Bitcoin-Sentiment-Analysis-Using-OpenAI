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
You can adjust the number of tweets retrieved by changing the value of count in the `api.search_tweets` function. You can also change the search word here to include other search terms such as BTC.