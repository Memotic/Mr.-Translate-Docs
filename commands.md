---
description: All of Mr. Translate's commands
---

# Commands

## Syntax

Paramaters surrounded by `<>` such as `<content>` are required. Parameters surrounded by `[]` are optional. Do not include the `<>` or `[]` when running commands.

## Translating - [How to Translate](how-to.md)

`/<language> <content>` - Translate `<content>` to `<language>` . Language can be a language name or code \(See [Languages](languages.md) for a list of supported languages\). Auto-detects the language of `<content`.

`/from <fromLanguage> <toLanguage> <content>` - Translate `<content>` to `<toLanguage>` from `<fromLanguage>` without auto-detecting the language of `<content`.

`/detect <content>` - Detect the language of `<content>`.

`/languages` - DMs a link to the [supported languages page](languages.md).

## View Server Quota

`/quota` - View the remaining, total, and used quota for all providers \(default\) or `[provider]`.

## Settings

Only members with the Manage Server permission can use these commands

`/prefix [newPrefix]` - View or set the prefix. Default is `/`. Mentioning the bot is always a valid prefix. Ex: `@Mr. Translate#2763 help`.

`/provider [provider]` - View or set the preferred provider. This sets the default provider to be used when translating. If a language is not supported with the preferred provider, an alternitve one will be used instead.

`/flags [on|off]` - Enable or disable flag translations \(See [How to Translate](how-to.md#using-flag-reactions-to-translate)\) for the entire server.

`/profanity [off|spoiler|on]` - View or set the basic profanity filter \(Azure Provider only!\). Setting to `spoiler` wraps profane words around spoiler tags, `on` replaces them with `*`. Mr. Translate _cannot_ provide a guarantee on this feature.

`/blacklist [users|channels|roles]` - View the blacklist or add/remove any number of users, channels and roles to/from the blacklist. The blacklist prevents members from interacting with the bot \(including flag translations\). You may use mentions or IDs as the parameters.

## Misc. Commands

`/help` - View basic help & links.

`/info` or `/stats` - View global bot stats.

`/donate` - DMs a link to Mr. Translate's PayPal

`/invite` - DMs links to invite Mr. Translate and to the Support Server.

`/check_perms` - Check if a member is blacklisted.

`/ping` - 🏓 Pong!





