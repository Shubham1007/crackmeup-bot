# crackmeup-bot

A twitter bot - [crackmeupbot](https://twitter.com/crackmeupbot) that tweets an endless stream of dank jokes using the [crackmeup-api](https://github.com/bholagabbar/crackmeup-api)

## Setup

1. Get your Twitter App API credentials from [dev.twitter.com](https://dev.twitter.com)
2. Add the corresponding keys/credentials as env variables
    * YOUR_ACCESS_TOKEN
    * YOUR_ACCESS_TOKEN_SECRET
    * YOUR_CONSUMER_KEY
    * YOUR_CONSUMER_SECRET
3. run `python tweet_bot.py && python reply_bot.py &&` or build and run with [Docker](https://docker.com) using `sudo docker build -t crackmeup-bot && docker run crackmeup-bot`

## (Beta) Tweeting to the bot to get back a personalised Joke

Example:
> @crackmeupbot #crackmeup with a blond joke
Categories available on the API README page.
