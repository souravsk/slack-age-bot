## Build a Slack Bot which will give your age
When you Give this bot Your Year of Birth it will return you current age.
## Prerequisite
- You have to have a slack channel where you should be the admin of that channel.
- You have to the bot token by creating the bot in slack 
- You have to have the app token 

# Add Token 
Now we will use those Tokens in our go code to access the bot and perform the our work.
Copy you own token from the slack app
```
  os.Setenv("SLACK_BOT_TOKEN", "<bot token>")
	os.Setenv("SLACK_APP_TOKEN", "<app token>")
```

Save the main file and run the program
```
go run main.go
```
Now go to your slack channel call the bot which `@<botname>`
```
@age-bot my yob is 1998
```
it will return `24`
So it work very nice.
