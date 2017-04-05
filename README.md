# discourse-telegram-notifications
A plugin for Discourse which allows users to receive their notifications by telegram message

# Getting setup
1. Install the plugin using the instructions here: [How to install a plugin](https://meta.discourse.org/t/install-a-plugin/19157)
1. Create a telegram by talking to the [BotFather](https://telegram.me/botfather) (instructions [here](https://core.telegram.org/bots#6-botfather)
2. Paste the "token" into the site setting "telegram access token"
3. Tick "telegram notifications enabled"

You can set the name/picture/description of your bot using the instructions [here](https://core.telegram.org/bots#botfather-commands)

# For users to receive notifications
1. Send a message to the bot, you'll recieve a message back that looks like
```
To get notifications for Discourse, enter the 'Chat ID' 1234567 in your user preferences
```
2. Visit your user preferences, and paste the number in the `Telegram Notifications` box
3. You should now receive notifications by telegram message!
