# Pesterchum-Discord

A Discord client mimicking the Pesterchum chat client from Homestuck, Uses a lot of code from my Pesterchum Client

#Tokens
The Discord API has officially deprecated user logins, (email / password) best choice is to use tokens. All accounts
have tokens, to find yours:

1. Open Discord
2. Press Ctrl+Shift+i
3. Click "Application" tab
4. Expand Storage > Local Storage > https://discordapp.com
5. Find "token" under "key"
6. Copy the text in quotes on the same row

#Quirks

Pesterchum-Discord lets you do custom quirks using Regex! (Regular Expression) for help on quirks (they work identically) check out
[illuminatedWax's quirk info](https://github.com/illuminatedwax/pesterchum#quirks-1) on the original Pesterchum. Misspeller has not yet been added

Add custom quirk commands by going to the pyquirks folder and removing quirk_funcs.pyc and replacing it with your own quirk_funcs.py
(if you want parts from the original just grab the [source](https://github.com/henry232323/Pesterchum-Discord/blob/master/pyquirks/quirk_funcs.py))