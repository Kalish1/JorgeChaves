# JorgeChaves
This is a scraping and cleaning discord bot.

## Web scraping
The bot scrapes news and gaming websites and put the content in form of messages on discord channels.

## Cleaning
Selected channels will have all messages deleted after a configured amount of time.

## Template
It is configured to work with [this template](https://discord.new/ZRshbvRZE37S).
It will fetch for new released trending games on metacritic and reddit information from communities such as r/world-news and r/steam-deals.
It is also integrated with tweepy, so it will fetch new posts on twitter of world news and specific games. 

## Configuration
Make sure to put your keys and tokens in order for it to work. See more information for [how to create a discord bot](https://discordpy.readthedocs.io/en/latest/discord.html) and [generate twitter keys and tokens](http://docs.tweepy.org/en/v3.5.0/auth_tutorial.html#auth-tutorial)
```javascript
discord_token = os.environ['disctoken']
consumer_key = os.environ['twikey']
consumer_secret = os.environ['twisecret']
access_token = os.environ['twitoken']
access_token_secret = os.environ['twitokensecret']
```
###### Running
You can run this bot on your own by placing your keys and tokens or set it on Heroku adding *Config Vars* `disctoken twikey twisecret twitoken twitokensecret` for your keys and tokens. 
