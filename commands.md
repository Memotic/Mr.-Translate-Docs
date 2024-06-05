---
description: All of Mr. Translate's commands
---

# Commands

## Syntax

Paramaters surrounded by `<>` such as `<content>` are required. Parameters surrounded by `[]` are optional. Do not include the `<>` or `[]` when running commands.

## Translating - [How to Translate](how-to.md)

`/<language> <content>` - Translate `<content>` to `<language>` . Language can be a language name or code \(See [Languages](languages.md) for a list of supported languages\). Auto-detects the language of `<content`.

Note: The prefix of `/` can be changed with `/settings quick-translate-prefix [newPrefix]`.

`/translate <to> <text> [source] [destination] [provider]` - Translate `<text>` to the `<to>` language.

- `<to>` - Destination language name or code. \(See [Languages](languages.md) for a list of supported languages\).
- `<text>` - Text to translate
- `[source]` - Optional source language name or code
- `[destination]` - Optional channel to send the translation to. You and Mr. Translate requires send messages permission in that channel.
- `[provider]` - Optional provider to translate with. Choices are "azure" and "google"

## View Remaining Characters

`/characters` - View the remaining, total, and used quota for all providers \(default\) or `[provider]`.

## Settings

Only members with the Manage Server permission can use these commands

`/settings quick-translate-prefix [newPrefix]` - View or set the prefix. Default is `/`. Mentioning the bot is always a valid prefix. Ex: `@Mr. Translate#2763 help`.

`/settings provider [provider]` - View or set the preferred provider. This sets the default provider to be used when translating. If a language is not supported with the preferred provider, an alternitve one will be used instead.

`/settings flags [on|off]` - Enable or disable flag translations \(See [How to Translate](how-to.md#using-flag-reactions-to-translate)\) for the entire server.

`/settings profanity [off|spoiler|on]` - View or set the basic profanity filter \(Azure Provider only!\). Setting to `spoiler` wraps profane words around spoiler tags, `on` replaces them with `*`. Mr. Translate _cannot_ provide a guarantee on this feature.

`/settings limit_large_translations [threshold] [admin_approval]` - Threshold should be set to zero to disable approvals of large translations.

`/settings view` - View the server settings

## Misc. Commands

`/help` - View basic help & links.

`/invite` - DMs links to invite Mr. Translate and to the Support Server.

## Premium Commands

`/premium info` - View info about Mr. Translate premium, Server premium status, and your premium subscriptions

`/premium billing` - Manage your premium subscriptions.

`/premium apply [subscription]` - Apply a premium subscription to your server. `[subscription]` is an optional subscription ID.

`/premium remove` - Remove premium from your server.
