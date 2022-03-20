
# Telegram Music Downloader
A Simple Music Downloader Bot For Telegram with Youtube Music And Spotify Support.


## Deployment

To deploy this project run

### Easy Way (Local)
```bash
  cp sample_config.env config.env
  pip3 install -r requirements.txt
  python3 -m bot
```

### Docker
```bash
  cp sample_config.env config.env
  docker build . -t musicbot
  docker run musicbot
```
### Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/aafusam/Phono-Music-Bot/)

### Railway
May not work because this project required Ytdl.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Faafusam%2FPhone-Music-Bot%2F&plugins=mongodb&envs=API_ID%2CAPI_HASH%2CBOT_TOKEN%2CSPOTIPY_CLIENT_SECRET%2CSPOTIPY_CLIENT_ID%2CAUTH_CHATS%2CUPDATES_CHANNEL%2CLOG_GROUP%2CDATABASE_URL&optionalEnvs=UPDATES_CHANNEL&API_IDDesc=Your+Telegram+API+ID&API_HASHDesc=Get+this+value+from+my.telegram.org%21+Please+do+not+steal&BOT_TOKENDesc=Make+a+bot+at+http%3A%2F%2Ftelegram.dog%2FBotFather+and+get+the+token+of+your+bot.Worth+it.+Get+it.&SPOTIPY_CLIENT_SECRETDesc=Your+Spotify+Client+Secret&SPOTIPY_CLIENT_IDDesc=Your+Spotify+Client+ID&AUTH_CHATSDesc=Authorized+chats&UPDATES_CHANNELDesc=Force+subscription+to+updates+channel&LOG_GROUPDesc=Downloaded+Music+Log+Group&DATABASE_URLDesc=MongoDB+URL&SPOTIPY_CLIENT_SECRETDefault=0f02b7c483c04257984695007a4a8d5c&SPOTIPY_CLIENT_IDDefault=4fe3fecfe5334023a1472516cc99d805&referralCode=rozari0)
## Environment Variables

To run this project, you will need to add the following environment variables to your config.env file

`API_ID`
`API_HASH`
`BOT_TOKEN`
`SPOTIPY_CLIENT_ID`
`SPOTIPY_CLIENT_SECRET`
`UPDATES_CHANNEL`
`LOG_GROUP`
`DATABASE_URL`
`AUTH_CHATS`



## License

[MIT](https://choosealicense.com/licenses/mit/)

