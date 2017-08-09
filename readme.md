## favorite-tweets

very simple twitter bot that favorites the ten most recent tweets containing a specific query string.

## usage

`git clone https://github.com/evanwinter/favorite-tweets.git`

`cd favorite-tweets`

[https://apps.twitter.com/app/new|create a new twitter app].

put the consumer key + secret and the access token + secret in a file called `config.js`, like so:

``
module.exports = {
	consumer_key: 'XXX',
	consumer_secret: 'XXX',
	access_token_key: 'XXX',
	access_token_secret: 'XXX'
}
``

run `npm i`