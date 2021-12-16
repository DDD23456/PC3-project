# PC3-project

## Summary

Created a NEWS Folder in which live TV links in m3u8 format are stored.

A m3u8 player (eg VLC Player) is required to play the m3u8 files. Just need to copy the raw url files from the NEWS Folder and paste into the video player.

The m3u8 links needs updating once it is not working.

After links are updated, the user is notified through the telegram.

Setup a telegram notification alert through using a telegram bot.

Any new update will generate a message through telegram alert to the user's phone.


## Problems

A big obstacles encounter was in setting up of the telegram bot like identifying the correct robot chat ID. Needs patience and lots of trial and error.


## Steps in creating the notification system using telegram

1)Create a new repository and 

2)Then under "Actions" , set up a new workflow folder named "notifier.yml" 

3)Paste or write codes into the folder "notifier.yml"

4)Next click on Telegram Bot Father https://t.me/botfather to create a personal telegram Bot as well as to get the Bot token.

5)Inside the terminal, type "curl https://api.telegram.org/bot"bottoken"/getUpdates" to obtain the Bot chat ID.

6)Having obtain the token and ID, go under "settings" and then "SECRETS", "ACTIONS" and then create a "NEW REPOSITORY SECRET" for the token and chat ID.

7)Done, now user's telegram will receive message whenever there is a update.



