---
description: A premium-only feature to supercharge your server's communication.
---

# Auto Translate

{% hint style="danger" %}
**Auto Translate is a premium-only feature. Sign up at** [**https://mrtranslate.bot/premium**](https://mrtranslate.bot/premium)****
{% endhint %}

## **How it works**

You can setup Auto Translate entries on any server with premium to translate messages to any supported langauge and even send different translations to different channels.

## Set up

Ensure Mr. Translate has the following permissions in _each_ channel you want Auto Translate to function. This includes channels for the source and destination translations.

1. Read Message History
2. Send Messages
3. Embed Links

### First Auto Translate Entry

Use the slash command `/auto-translate add` to create an Auto Translate entry.\
Parameteres include:\
`to` - the language to translate to\
`from` - the language to translate from. Setting this to anything but "Any" will only translate messages detected to be this language\
`source` - the source channel. Leave blank to translate messages from the current channel\
`destination` - the destination channel. Use this to send translations to a different channel. Leave blank to send translations to this channel\
`translate_bots` - enable to translate messages from bots. By default Mr. Translate will not translate messages sent by other bots. Mr. Translate will never automatically translate a message it sends.

