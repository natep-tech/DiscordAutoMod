# Discord AutoMod Custom Lists
## WARNING: NSFW
*These files contain strong swears and slurs. You have been warned.*

These are custom lists I've compiled from various sources, as a replacement for the built-in lists Discord provides. A few of the built-in lists are too restrictive, blocking phrases like "to f\*ck" and other arbitrary phrases within their severe profanity category. 
https://raw.githubusercontent.com/natep-tech/DiscordAutoMod/main/Guide.png

## Discord Warnings list
This uses Discord's built-in Insults & Slurs and Sexual Content lists. It only sends a warning log message to a moderator channel, but doesn not block the message from being sent in chat.

## Bad Words list
This list blocks the message from being sent, and also logs the message in the moderator channel.
https://raw.githubusercontent.com/natep-tech/DiscordAutoMod/main/Blocked.png

## Sexual (Horny) Words list
Similar to the Bad Words list, this blocks the message from being sent, and also logs the message in the moderator channel. There are three parts to this list:
1. The main content __Sexual Words (Text)__
2. The regex to block any sexual body part combined with a adjective (Big boobs, small dick) __Sexual Words (Regex)__
3. A couple allowed phrases to avoid the regex being too restrictive __Sexual Words (Allowed)__
https://raw.githubusercontent.com/natep-tech/DiscordAutoMod/main/Blocked.png

## Custom Warnings list
This is a custom list of messages that will be flagged and send a warning log to the moderator channel, but does not block the message from being sent in chat.
https://raw.githubusercontent.com/natep-tech/DiscordAutoMod/main/Warnings.png

## Bad Links list
This utilizes the regex function of the custom word lists, blocking spoofed links using the Fancy Markdown.
https://raw.githubusercontent.com/natep-tech/DiscordAutoMod/main/Blocked.png
