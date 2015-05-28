# slackbot
Slack Slash Command Bot in Go

# Testing on localhost
Using httpie
```bash
http -f POST http://localhost:3000/bot/command token=debug team_id=T0001 team_domain=example channel_id=C2147483705 channel_name=test user_id=U2147483697 user_name=Chris command=/weather text=94070
```
