# sopel-discord

Sopel module for connecting Discord and IRC channels.

This module requires a Discord App Bot account token.
The Discord Bot account must also have the "Manage webhooks" permissions on any relevant channels.

## Requirements

* Python 3.6 or later
* [discord.py](https://github.com/Rapptz/discord.py) 1.x
* [Sopel](https://github.com/sopel-irc/sopel) 7.x

## Configuration
This module is configured via a `[discord]` section in the Sopel configuration file.
```
[discord]
# Discord Bot token
discord_token = AbCd1234.5678.AbcD1234
# Comma-separated list of <Discord channel ID>:<IRC channel> mappings
channel_mappings = 1234:#irc-chan1, 5678:#irc-chan2
```
