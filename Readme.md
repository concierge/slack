## Slack Integration
#### Installation
The easiest way to install this integration is to use KPM.
```sh
/kpm install slack
```

#### Configuration
To add a configuration, execute each of the following commands (replace each of the angle bracketed strings with the respective information and update your slack team configuration to match):
```sh
/kpm config slack name "<botName>"
/kpm config slack slack_tokens ["<yourSlackTeamToken1>", "yourSlackTeamToken2", ...]
/kpm config slack port "<portNumber>"
/kpm config slack commandPrefix "!"
```

Tokens can be issued from here https://slack.com/apps/A0F7YS25R-bots  
You will need to give the bot a user name. Invite the bot to channels which you want it to respond to commands in.

#### Running
To run Slack, either run `node main.js slack` when starting Concierge or run `/kpm start slack` when Concierge is running.
