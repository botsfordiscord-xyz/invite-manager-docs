# Strikes

# What are strikes?

Strikes are points that users get for violating server rules. Every time the user receives a strike, he gets a personal message telling him how many strikes he has and why he got them. When a user reaches a certain amount of strikes, he will receive a **punishment**.

# What are violations?

Violations are rules that you can enable or disable on your server. Currently, the following violations exist:

### invites

This violation is triggered whenever the user posts an invite link to another discord server.

**Config options:**

- [autoModInvitesEnabled](https://docs.invitemanager.co/bot/other/configs#automodinvitesenabled)


### links

This violation is triggered whenever the user posts a link.

**Config options:**

- [autoModLinksEnabled](https://docs.invitemanager.co/bot/other/configs#automodlinksenabled)
- [autoModLinksWhitelist](https://docs.invitemanager.co/bot/other/configs#automodlinkswhitelist)
- [autoModLinksBlacklist](https://docs.invitemanager.co/bot/other/configs#automodlinksblacklist)
- [autoModLinksFollowRedirects](https://docs.invitemanager.co/bot/other/configs#automodlinksfollowredirects)


### words

This violation is triggered whenever the user posts blacklisted words.

**Config options:**

- [autoModWordsEnabled](https://docs.invitemanager.co/bot/other/configs#automodwordsenabled)
- [autoModWordsBlacklist](https://docs.invitemanager.co/bot/other/configs#automodwordsblacklist)


### allCaps

This violation is triggered whenever the user posts a message that is mostly in CAPS.

**Config options:**

- [autoModAllCapsEnabled](https://docs.invitemanager.co/bot/other/configs#automodallcapsenabled)
- [autoModAllCapsMinCharacters](https://docs.invitemanager.co/bot/other/configs#automodallcapsmincharacters)
- [autoModAllCapsPercentageCaps](https://docs.invitemanager.co/bot/other/configs#automodallcapspercentagecaps)


### duplicateText

This violation is triggered whenever the user posts the same text multiple times.

**Config options:**

- [autoModDuplicateTextEnabled](https://docs.invitemanager.co/bot/other/configs#automodduplicatetextenabled)
- [autoModDuplicateTextTimeframeInSeconds](https://docs.invitemanager.co/bot/other/configs#automodduplicatetexttimeframeinseconds)


### quickMessages

This violation is triggered whenever the user quickly posts messages.

**Config options:**

- [autoModQuickMessagesEnabled](https://docs.invitemanager.co/bot/other/configs#automodquickmessagesenabled)
- [autoModQuickMessagesNumberOfMessages](https://docs.invitemanager.co/bot/other/configs#automodquickmessagesnumberofmessages)
- [autoModQuickMessagesTimeframeInSeconds](https://docs.invitemanager.co/bot/other/configs#automodquickmessagestimeframeinseconds)


### mentionUsers

This violation is triggered whenever the user mentions mutliple users.

**Config options:**

- [autoModMentionUsersEnabled](https://docs.invitemanager.co/bot/other/configs#automodmentionusersenabled)
- [autoModMentionUsersMaxNumberOfMentions](https://docs.invitemanager.co/bot/other/configs#automodmentionusersmaxnumberofmentions)


### mentionRoles

This violation is triggered whenever the user mentions mutliple roles.

**Config options:**

- [autoModMentionRolesEnabled](https://docs.invitemanager.co/bot/other/configs#automodmentionrolesenabled)
- [autoModMentionRolesMaxNumberOfMentions](https://docs.invitemanager.co/bot/other/configs#automodmentionrolesmaxnumberofmentions)


### emojis

This violation is triggered whenever the user posts multiple emojis.

**Config options:**

- [autoModEmojisEnabled](https://docs.invitemanager.co/bot/other/configs#automodemojisenabled)
- [autoModEmojisMaxNumberOfEmojis](https://docs.invitemanager.co/bot/other/configs#automodemojismaxnumberofemojis)
