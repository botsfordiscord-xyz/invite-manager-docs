# Full Command Reference

To get a list of available commands, do `!help` on your server.

# Commands

## config

Aliases: `c`

Group: Config

Guild only: true

Usage: {prefix}config [key] [value] 

**Arguments**

**<key>**:
The config setting which you want to show/change.
Use one of the following values: `prefix`, `lang`, `getupdates`, `logchannel`, `joinmessage`, `joinmessagechannel`, `leavemessage`, `leavemessagechannel`, `leaderboardstyle`, `hideleftmembersfromleaderboard`, `autosubtractfakes`, `autosubtractleaves`, `autosubtractleavethreshold`, `rankassignmentstyle`, `rankannouncementchannel`, `rankannouncementmessage`, `mutedrole`, `captchaverificationonjoin`, `captchaverificationwelcomemessage`, `captchaverificationsuccessmessage`, `captchaverificationfailedmessage`, `captchaverificationtimeout`, `captchaverificationlogenabled`, `modlogchannel`, `modpunishmentbandeletemessage`, `modpunishmentkickdeletemessage`, `modpunishmentsoftbandeletemessage`, `modpunishmentwarndeletemessage`, `modpunishmentmutedeletemessage`, `automodenabled`, `automodmoderatedchannels`, `automodmoderatedroles`, `automodignoredchannels`, `automodignoredroles`, `automoddeletebotmessage`, `automoddeletebotmessagetimeoutinseconds`, `automodlogenabled`, `automoddisabledforoldmembers`, `automoddisabledforoldmembersthreshold`, `automoddisabledforoldmembersreceivesilentwarning`, `automodinvitesenabled`, `automodlinksenabled`, `automodlinkswhitelist`, `automodlinksblacklist`, `automodlinksfollowredirects`, `automodwordsenabled`, `automodwordsblacklist`, `automodallcapsenabled`, `automodallcapsmincharacters`, `automodallcapspercentagecaps`, `automodduplicatetextenabled`, `automodduplicatetexttimeframeinseconds`, `automodquickmessagesenabled`, `automodquickmessagesnumberofmessages`, `automodquickmessagestimeframeinseconds`, `automodmentionusersenabled`, `automodmentionusersmaxnumberofmentions`, `automodmentionrolesenabled`, `automodmentionrolesmaxnumberofmentions`, `automodemojisenabled`, `automodemojismaxnumberofemojis`

**<value>**:
The new value of the setting.


## interactiveConfig

Aliases: `ic`

Group: Config

Guild only: true

Usage: {prefix}interactiveConfig 

**Arguments**



## inviteCodeConfig

Aliases: `invite-code-config`, `invcodeconf`, `icc`

Group: Config

Guild only: true

Usage: {prefix}inviteCodeConfig [key] [code] [value] 

**Arguments**

**<key>**:
The config setting which you want to show/change.
Use one of the following values: `name`, `roles`

**<code>**:
The invite code that the setting is changed for.
**<value>**:
The new value of the setting.


## memberConfig

Aliases: `member-config`, `memconf`, `mc`

Group: Config

Guild only: true

Usage: {prefix}memberConfig [key] [user] [value] 

**Arguments**

**<key>**:
The config setting which you want to show/change.
Use one of the following values: `hidefromleaderboard`

**<user>**:
The member that the setting is shown/changed for.
**<value>**:
The new value of the setting.


## permissions

Aliases: `perms`, `p`

Group: Config

Guild only: true

Usage: {prefix}permissions [cmd] [role] 

**Arguments**

**<cmd>**:
The command to configure permissions for.
**<role>**:
The role which should be granted or denied access to the command.


## graph

Aliases: `g`, `chart`

Group: Other

Guild only: true

Usage: {prefix}graph <type> [duration] 

**Arguments**

**<type>**:
The type of chart to display.
Use one of the following values: `joins`, `leaves`, `usage`

**<duration>**:
The duration period for the chart.


## botInfo

Aliases: `bot-info`

Group: Info

Guild only: true

Usage: {prefix}botInfo 

**Arguments**



## getBot

Aliases: `get-bot`, `invite-bot`, `invitebot`

Group: Info

Guild only: false

Usage: {prefix}getBot 

**Arguments**



## help

Aliases: 

Group: Info

Guild only: false

Usage: {prefix}help [command] 

**Arguments**

**<command>**:
The command to get detailed information for.


## members

Aliases: `member`, `memberscount`

Group: Info

Guild only: true

Usage: {prefix}members 

**Arguments**



## prefix

Aliases: 

Group: Info

Guild only: true

Usage: {prefix}prefix 

**Arguments**



## setup

Aliases: `guide`, `test`, `testbot`, `test-bot`

Group: Info

Guild only: true

Usage: {prefix}setup 

**Arguments**



## support

Aliases: 

Group: Info

Guild only: false

Usage: {prefix}support 

**Arguments**



## addInvites

Aliases: `add-invites`

Group: Invites

Guild only: true

Usage: {prefix}addInvites <user> <amount> [reason] 

**Arguments**

**<user>**:
The user that will receive/lose the bonus invites.
**<amount>**:
The amount of invites the user will get/lose. Use a negative (-) number to remove invites.
**<reason>**:
The reason for adding/removing the invites.


## clearInvites

Aliases: `clear-invites`

Group: Invites

Guild only: true

Usage: {prefix}clearInvites [clearBonus] [user] 

**Arguments**

**<clearBonus>**:
Pass `true` if you want to remove bonus invites, otherwise `false` (default).
**<user>**:
The user to clear all invites from. If omitted clears all users.


## createInvite

Aliases: `create-invite`

Group: Invites

Guild only: true

Usage: {prefix}createInvite <name> [channel] 

**Arguments**

**<name>**:
The name of the invite code.
**<channel>**:
The channel for which the invite code is created. Uses the current channel by default.


## fake

Aliases: `fakes`, `cheaters`, `cheater`, `invalid`

Group: Invites

Guild only: true

Usage: {prefix}fake [page] 

**Arguments**

**<page>**:
Which page of the fake list to get.


## info

Aliases: `showinfo`

Group: Invites

Guild only: true

Usage: {prefix}info <user> 

**Arguments**

**<user>**:
The user for whom you want to see additional info.


## inviteCodes

Aliases: `invitecode`, `invite-code`, `invite-codes`, `getinvitecode`, `get-invite-code`, `get-invite-codes`, `showinvitecode`, `show-invite-code`

Group: Invites

Guild only: true

Usage: {prefix}inviteCodes 

**Arguments**



## inviteDetails

Aliases: `invite-details`

Group: Invites

Guild only: true

Usage: {prefix}inviteDetails [user] 

**Arguments**

**<user>**:
The user for whom you want to show detailed invites.


## invites

Aliases: `invite`, `rank`

Group: Invites

Guild only: true

Usage: {prefix}invites [user] 

**Arguments**

**<user>**:
The user for whom you want to show invites.


## leaderboard

Aliases: `top`

Group: Invites

Guild only: true

Usage: {prefix}leaderboard [page] [date] 

**Arguments**

**<page>**:
Which page of the leaderboard to get.
**<date>**:
The date (& time) for which the leaderboard is shown.


## restoreInvites

Aliases: `restore-invites`, `unclear-invites`, `unclearinvites`

Group: Invites

Guild only: true

Usage: {prefix}restoreInvites [user] 

**Arguments**

**<user>**:
The user to restore all invites to. If omitted restores invites for all users.


## subtractFakes

Aliases: `subtract-fakes`, `subfakes`, `sf`

Group: Invites

Guild only: true

Usage: {prefix}subtractFakes 

**Arguments**



## subtractLeaves

Aliases: `subtract-leaves`, `subleaves`, `sl`

Group: Invites

Guild only: true

Usage: {prefix}subtractLeaves 

**Arguments**



## punishmentConfig

Aliases: `punishment-config`

Group: Moderation

Guild only: true

Usage: {prefix}punishmentConfig [punishment] [strikes] [args] 

**Arguments**

**<punishment>**:
Type of punishment to use.
Use one of the following values: `ban`, `kick`, `softban`, `warn`, `mute`

**<strikes>**:
Number of strikes for this punishment to be used.
**<args>**:
Arguments passed to the punishment.


## strikeConfig

Aliases: `strike-config`

Group: Moderation

Guild only: true

Usage: {prefix}strikeConfig [violation] [strikes] 

**Arguments**

**<violation>**:
Violation type.
Use one of the following values: `invites`, `links`, `words`, `allcaps`, `duplicatetext`, `quickmessages`, `mentionusers`, `mentionroles`, `emojis`

**<strikes>**:
Number of strikes.


## ban

Aliases: 

Group: Moderation

Guild only: true

Usage: {prefix}ban <user> [deleteMessageDays] [reason] 

**Arguments**

**<user>**:
User to ban.
**<deleteMessageDays>**:
How far back messages will be deleted (in days).
**<reason>**:
Why was the user banned.


## kick

Aliases: 

Group: Moderation

Guild only: true

Usage: {prefix}kick <member> [reason] 

**Arguments**

**<member>**:
Member to kick.
**<reason>**:
Why the member was kicked.


## mute

Aliases: 

Group: Moderation

Guild only: true

Usage: {prefix}mute <user> [muteDuration] [reason] 

**Arguments**

**<user>**:
cmd.mute.self.args.user
**<muteDuration>**:
cmd.mute.self.args.muteDuration
**<reason>**:
cmd.mute.self.args.reason


## softBan

Aliases: `soft-ban`

Group: Moderation

Guild only: true

Usage: {prefix}softBan <user> [deleteMessageDays] [reason] 

**Arguments**

**<user>**:
User to ban.
**<deleteMessageDays>**:
How far back messages will be deleted (in days).
**<reason>**:
Why was the user banned.


## unban

Aliases: 

Group: Moderation

Guild only: true

Usage: {prefix}unban <user> [reason] 

**Arguments**

**<user>**:
cmd.unban.self.args.user
**<reason>**:
cmd.unban.self.args.reason


## unmute

Aliases: 

Group: Moderation

Guild only: true

Usage: {prefix}unmute <user> 

**Arguments**

**<user>**:
cmd.unmute.self.args.user


## warn

Aliases: 

Group: Moderation

Guild only: true

Usage: {prefix}warn <member> [reason] 

**Arguments**

**<member>**:
Member to warn.
**<reason>**:
Why was the member was warned.


## caseDelete

Aliases: `case-delete`, `deletecase`, `delete-case`

Group: Moderation

Guild only: true

Usage: {prefix}caseDelete <caseNumber> [reason] 

**Arguments**

**<caseNumber>**:
cmd.caseDelete.self.args.caseNumber
**<reason>**:
cmd.caseDelete.self.args.reason


## caseView

Aliases: `case-view`, `viewcase`, `view-case`

Group: Moderation

Guild only: true

Usage: {prefix}caseView <caseNumber> 

**Arguments**

**<caseNumber>**:
cmd.caseView.self.args.caseNumber


## check

Aliases: `history`

Group: Moderation

Guild only: true

Usage: {prefix}check [user] 

**Arguments**

**<user>**:
User to check.


## cleanShort

Aliases: `clean-short`, `clearshort`, `clear-short`

Group: Moderation

Guild only: true

Usage: {prefix}cleanShort <maxTextLength> [numberOfMessages] 

**Arguments**

**<maxTextLength>**:
cmd.cleanShort.self.args.maxTextLength
**<numberOfMessages>**:
cmd.cleanShort.self.args.numberOfMessages


## cleanText

Aliases: `clean-text`, `cleartext`, `clear-text`

Group: Moderation

Guild only: true

Usage: {prefix}cleanText <text> [numberOfMessages] 

**Arguments**

**<text>**:
cmd.cleanText.self.args.text
**<numberOfMessages>**:
cmd.cleanText.self.args.numberOfMessages


## clean

Aliases: `clear`

Group: Moderation

Guild only: true

Usage: {prefix}clean <type> [numberOfMessages] 

**Arguments**

**<type>**:
cmd.clean.self.args.type
Use one of the following values: `images`, `links`, `mentions`, `bots`, `embeds`, `emojis`, `reacted`, `reactions`

**<numberOfMessages>**:
cmd.clean.self.args.numberOfMessages


## purgeUntil

Aliases: `purge-until`, `prune-until`, `pruneu`, `purgeu`

Group: Moderation

Guild only: true

Usage: {prefix}purgeUntil <messageID> 

**Arguments**

**<messageID>**:
Last message ID to be deleted.


## purge

Aliases: `prune`

Group: undefined

Guild only: true

Usage: {prefix}purge <quantity> [member] 

**Arguments**

**<quantity>**:
How many messages should be deleted.
**<member>**:
User whose messages get deleted


## export

Aliases: 

Group: Premium

Guild only: true

Usage: {prefix}export <type> 

**Arguments**

**<type>**:
The type of export you want.
Use one of the following values: `leaderboard`

{% hint style="info" %} This command is available for premium users only. {% endhint %}

## premium

Aliases: `patreon`, `donate`

Group: Premium

Guild only: true

Usage: {prefix}premium 

**Arguments**



## tryPremium

Aliases: `try`, `try-premium`

Group: Premium

Guild only: true

Usage: {prefix}tryPremium 

**Arguments**



## addRank

Aliases: `add-rank`, `set-rank`, `setrank`

Group: Ranks

Guild only: true

Usage: {prefix}addRank <role> <invites> [info] 

**Arguments**

**<role>**:
The role which the user will receive when reaching this rank.
**<invites>**:
The amount of invites needed to reach the rank.
**<info>**:
A description that users will see so they know more about this rank.


## ranks

Aliases: `show-ranks`, `showranks`

Group: Ranks

Guild only: true

Usage: {prefix}ranks 

**Arguments**



## removeRank

Aliases: `remove-rank`

Group: Ranks

Guild only: true

Usage: {prefix}removeRank [rank] 

**Arguments**

**<rank>**:
The for which you want to remove the rank.


## makeMentionable

Aliases: `make-mentionable`, `mm`

Group: Other

Guild only: true

Usage: {prefix}makeMentionable <role> 

**Arguments**

**<role>**:
The role that you want to mention.


## mentionRole

Aliases: `mention-role`, `mr`

Group: Other

Guild only: true

Usage: {prefix}mentionRole <role> 

**Arguments**

**<role>**:
The role that you want to mention.


