# YT-INline-bot
## Deploy the bot  
Create a bot on telegram using [@botfather](t.me/botfather)    
Create an app on [heroku](https://dashboard.heroku.com/)   
Create a public channel on telegram  
Set environment variables in heroku app  
- BOT_TOKEN = your bot API token  
- HEROKU_APP_NAME = name of your heroku app  
- POLLING : if you're running this on your local machine, please set POLLING = True else leave this if you're deploying on heroku  
- AUDIO_DB : PostgreSQL DB link for audio management
- USER_DB : PostgreSQL DB link for user management  
- OPEN_CHANNEL_USERNAME : Universal upload channel username, bot will upload files here and forward it to the user
