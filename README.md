# Twitter_follower_comparison

This notebook contains code that pulls the follwers and all their information for two moderately large Twitter accounts. To use this code you will need to create a .py file containing your Twitter API credentials. You can see mine is imported in the line,

'from API_keys_Brenden import api_key, api_key_secret, access_token, access_token_secret'

With the rate limit for the Twitter API making you sleep for 15 mins every time the rate limit is exceeded, this code may take a couple hours to finish running for the current accounts used.

Requirements:
- Tweepy
- datetime
- time


