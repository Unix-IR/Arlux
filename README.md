# [ArluxBot](https://telegram.me/UnixIR)

**An advanced and powerful administration bot based on NEW TG-CLI


* * *

## Commands

| Use help |
|:--------|:------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh# Let's install the bot.
cd $HOME
git clone https://github.com/saleh0/Arlux.git
cd Arlux
chmod +x beyond.sh
./arlux.sh install
./arlux.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```shcd $HOME && git clone https://github.com/Unix-IR/arlux.git && cd Arlux && chmod +x arlux.sh && ./arlux.sh install && ./arlux.sh
```

* * *

### Sudo And Bot
After you run the bot for first time, send it `!id`. Get your ID and stop the bot.

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    157059515,
    0,
    YourID
  }
```
add your bot ID at line 4 and add your ID at line 87 in bot.lua
add your ID at line 2 in tools.lua
Then restart the bot.


* * *

### Our Telegram channel:

[@UnixIR](https://telegram.me/UnixIR)
