# Discord AutoMod Custom Lists
## WARNING: NSFW
*These files contain strong swears and slurs. You have been warned.*

These are custom lists I've compiled from various sources, as a replacement for the built-in lists Discord provides. A few of the built-in lists are too restrictive, blocking phrases like "to f\*ck" and other arbitrary phrases within their severe profanity category. Create a new custom Rule list for each category, as shown. 

The settings panel for this can be found at (Server Settings > Safety Setup > AutoMod) See the [offical Discord support link](https://support.discord.com/hc/en-us/articles/4421269296535-AutoMod-FAQ) for more details.

![A screenshot of the Discord UI when creating a new custom AutoMod Rule.](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Guide.png)


## Discord Warnings list
This uses Discord's built-in Insults & Slurs and Sexual Content lists. It only sends a warning log message to a moderator channel, but doesn not block the message from being sent in chat.

![A screenshot of the Discord UI displaying the settings for the default Discord Warning list.](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/DiscordWarnings.png)


## [Bad Words list](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Lists/Bad%20Words.txt)
This list blocks the message from being sent, and also logs the message in the moderator channel.

![A screenshot of the Discord UI displaying the settings for a blocked list.](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Blocked.png)


## Sexual (Horny) Words list
Similar to the Bad Words list, this blocks the message from being sent, and also logs the message in the moderator channel. There are three parts to this list:
1. The main content [__Sexual Words (Text)__](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Lists/Sexual%20Words%20(Text).txt)
2. The regex to block any sexual body part combined with a adjective (Big boobs, small dick) [__Sexual Words (Regex)__](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Lists/Sexual%20Words%20(Rexex).txt)
3. A couple allowed phrases to avoid the regex being too restrictive [__Sexual Words (Allowed)__](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Lists/Sexual%20Words%20(Allowed).txt)

![A screenshot of the Discord UI displaying the settings for a blocked list.](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Blocked.png)


## [Custom Warnings list](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Lists/Custom%20Warnings.txt)
This is a custom list of messages that will be flagged and send a warning log to the moderator channel, but does not block the message from being sent in chat.

![A screenshot of the Discord UI displaying the settings for a warning list.](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Warnings.png)


## [Bad Links list](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Lists/Bad%20Links.txt)
This utilizes the regex function of the custom word lists, blocking spoofed links using the Fancy Markdown.

![A screenshot of the Discord UI displaying the settings for a blocked list.](https://github.com/natep-tech/DiscordAutoMod/blob/022d9adb38ad0a10103073c95200f3a650f0b5d6/Blocked.png)
