# Strikes

# What are strikes?

Strikes are points that users get for violating server rules. Every time the user receives a strike, he gets a personal message telling him how many strikes he has and why he got them. When a user reaches a certain amount of strikes, he will receive a **punishment**.

# What are violations?

Violations are rules that you can enable or disable on your server. Currently, the following violations exist:

## invites

This violation is triggered whenever the user posts an invite link to another discord server.

### autoModInvitesEnabled

If enabled, invite links will be auto-moderated.

Type: `Boolean`

Default: `true`

**Configuration**

Reset to default:
`!config autoModInvitesEnabled default`

Enable:

`!config autoModInvitesEnabled true`

Disable:

`!config autoModInvitesEnabled false`





## links

This violation is triggered whenever the user posts a link.

### autoModLinksEnabled

If enabled, links will be auto-moderated.

Type: `Boolean`

Default: `true`

**Configuration**

Reset to default:
`!config autoModLinksEnabled default`

Enable:

`!config autoModLinksEnabled true`

Disable:

`!config autoModLinksEnabled false`



### autoModLinksWhitelist

A comma separated list of links that are allowed to be posted.

Type: `List of String`

Default: `null`

**Configuration**

Reset to default:
`!config autoModLinksWhitelist default`

Examples:

`!config autoModLinksWhitelist discordbots.org`

`!config autoModLinksWhitelist youtube.com,twitch.com`



### autoModLinksBlacklist

A comma separated list of links that are not allowed to be posted.

Type: `List of String`

Default: `null`

**Configuration**

Reset to default:
`!config autoModLinksBlacklist default`

Examples:

`!config autoModLinksBlacklist google.com`

`!config autoModLinksBlacklist twitch.com,youtube.com`



### autoModLinksFollowRedirects

If enabled, our bot will follow redirects to see where a link leads (to prevent people from using link-shorteners.)

Type: `Boolean`

Default: `true`

**Configuration**

Reset to default:
`!config autoModLinksFollowRedirects default`

Enable:

`!config autoModLinksFollowRedirects true`

Disable:

`!config autoModLinksFollowRedirects false`

{% hint style="info" %} This feature is only available for premium users. {% endhint %}



## words

This violation is triggered whenever the user posts blacklisted words.

### autoModWordsEnabled

If enabled, certain words will be auto-moderated.

Type: `Boolean`

Default: `true`

**Configuration**

Reset to default:
`!config autoModWordsEnabled default`

Enable:

`!config autoModWordsEnabled true`

Disable:

`!config autoModWordsEnabled false`



### autoModWordsBlacklist

A comma separated list of words that will be auto-moderated.

Type: `List of String`

Default: `null`

**Configuration**

Reset to default:
`!config autoModWordsBlacklist default`

Examples:

`!config autoModWordsBlacklist gay`

`!config autoModWordsBlacklist stupid,fuck`





## allCaps

This violation is triggered whenever the user posts a message that is mostly in CAPS.

### autoModAllCapsEnabled

If enabled, messages written in all/mostly CAPS will be auto-moderated.

Type: `Boolean`

Default: `true`

**Configuration**

Reset to default:
`!config autoModAllCapsEnabled default`

Enable:

`!config autoModAllCapsEnabled true`

Disable:

`!config autoModAllCapsEnabled false`



### autoModAllCapsMinCharacters

How long a message needs to be until this violation is activated.

Type: `Number`

Default: `10`

**Configuration**

Reset to default:
`!config autoModAllCapsMinCharacters default`

Examples:

`!config autoModAllCapsMinCharacters 5`

`!config autoModAllCapsMinCharacters 15`



### autoModAllCapsPercentageCaps

Percentage of letters that need to be CAPS to be triggered.

Type: `Number`

Default: `70`

**Configuration**

Reset to default:
`!config autoModAllCapsPercentageCaps default`

Examples:

`!config autoModAllCapsPercentageCaps 50`

`!config autoModAllCapsPercentageCaps 90`





## duplicateText

This violation is triggered whenever the user posts the same text multiple times.

### autoModDuplicateTextEnabled

If enabled, duplicate text will be auto-moderated.

Type: `Boolean`

Default: `true`

**Configuration**

Reset to default:
`!config autoModDuplicateTextEnabled default`

Enable:

`!config autoModDuplicateTextEnabled true`

Disable:

`!config autoModDuplicateTextEnabled false`



### autoModDuplicateTextTimeframeInSeconds

Time (in seconds) within the same text of the same author will be auto-moderated.

Type: `Number`

Default: `60`

**Configuration**

Reset to default:
`!config autoModDuplicateTextTimeframeInSeconds default`

Examples:

`!config autoModDuplicateTextTimeframeInSeconds 5`

`!config autoModDuplicateTextTimeframeInSeconds 20`





## quickMessages

This violation is triggered whenever the user quickly posts messages.

### autoModQuickMessagesEnabled

If enabled, message sent quickly after another will be auto-moderated.

Type: `Boolean`

Default: `true`

**Configuration**

Reset to default:
`!config autoModQuickMessagesEnabled default`

Enable:

`!config autoModQuickMessagesEnabled true`

Disable:

`!config autoModQuickMessagesEnabled false`



### autoModQuickMessagesNumberOfMessages

How many messages within the specified amount of time will be considered spam and are auto-moderated.

Type: `Number`

Default: `5`

**Configuration**

Reset to default:
`!config autoModQuickMessagesNumberOfMessages default`

Examples:

`!config autoModQuickMessagesNumberOfMessages 5`

`!config autoModQuickMessagesNumberOfMessages 10`



### autoModQuickMessagesTimeframeInSeconds

During what timeframe (in seconds) quick messages will be counted.

Type: `Number`

Default: `3`

**Configuration**

Reset to default:
`!config autoModQuickMessagesTimeframeInSeconds default`

Examples:

`!config autoModQuickMessagesTimeframeInSeconds 2`

`!config autoModQuickMessagesTimeframeInSeconds 10`





## mentionUsers

This violation is triggered whenever the user mentions mutliple users.

### autoModMentionUsersEnabled

If enabled, too many user mentions will be auto-moderated.

Type: `Boolean`

Default: `true`

**Configuration**

Reset to default:
`!config autoModMentionUsersEnabled default`

Enable:

`!config autoModMentionUsersEnabled true`

Disable:

`!config autoModMentionUsersEnabled false`



### autoModMentionUsersMaxNumberOfMentions

Maximum amount of user mentions per message.

Type: `Number`

Default: `5`

**Configuration**

Reset to default:
`!config autoModMentionUsersMaxNumberOfMentions default`

Examples:

`!config autoModMentionUsersMaxNumberOfMentions 2`

`!config autoModMentionUsersMaxNumberOfMentions 5`





## mentionRoles

This violation is triggered whenever the user mentions mutliple roles.

### autoModMentionRolesEnabled

If enabled, too many role mentions will be auto-moderated.

Type: `Boolean`

Default: `true`

**Configuration**

Reset to default:
`!config autoModMentionRolesEnabled default`

Enable:

`!config autoModMentionRolesEnabled true`

Disable:

`!config autoModMentionRolesEnabled false`



### autoModMentionRolesMaxNumberOfMentions

Maximum amount of role mentions per message.

Type: `Number`

Default: `3`

**Configuration**

Reset to default:
`!config autoModMentionRolesMaxNumberOfMentions default`

Examples:

`!config autoModMentionRolesMaxNumberOfMentions 2`

`!config autoModMentionRolesMaxNumberOfMentions 5`





## emojis

This violation is triggered whenever the user posts multiple emojis.

### autoModEmojisEnabled

If enabled, too many emojis will be auto-moderated.

Type: `Boolean`

Default: `true`

**Configuration**

Reset to default:
`!config autoModEmojisEnabled default`

Enable:

`!config autoModEmojisEnabled true`

Disable:

`!config autoModEmojisEnabled false`



### autoModEmojisMaxNumberOfEmojis

Maximum amount of emojis per message.

Type: `Number`

Default: `5`

**Configuration**

Reset to default:
`!config autoModEmojisMaxNumberOfEmojis default`

Examples:

`!config autoModEmojisMaxNumberOfEmojis 5`

`!config autoModEmojisMaxNumberOfEmojis 10`
