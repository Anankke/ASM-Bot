# ASM-Bot

![https://github.com/Anankke/ASM-Bot/blob/master/LICENSE](https://img.shields.io/github/license/Anankke/ASM-Bot) ![https://python.org](https://img.shields.io/badge/python-3.6%20%7C%203.7%20%7C%203.8-blue.svg) ![https://github.com/pyrogram/pyrogram/](https://img.shields.io/badge/pyrogram-asyncio-blue.svg)

> Anti Service Message Bot

自动删除 Telegram 群组中的服务消息，如加群退群信息等。

## Installation

```
pip3 install -U https://github.com/pyrogram/pyrogram/archive/asyncio.zip TgCrypto
git clone https://github.com/Anankke/ASM-Bot.git
cd ASM-Bot
cp config.py.example config.py
vim config.py
python3 asm.py
```

Get your own Telegram API key from https://my.telegram.org/apps, get your bot token from [@BotFather](https://t.me/BotFather), fill them in `config.py`.
