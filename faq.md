# FAQ

This is a list of frequently asked questions.

## How do I change the prefix of the bot?

You can do `!config prefix -` to change the prefix. If you don't know your current prefix, you can do `@InviteManager prefix` to see the prefix.

## How do I set join and leave messages?

Set the channel by doing `!config joinMessageChannel #channel` or `!config leaveMessageChannel #channel`. After doing that, new joins and leaves will be posted to that channel.

## Can I customize the join and leave messages?

Absolutely! You can change the message by doing for example
`!config joinMessage {memberMention} **joined**; Invited by **{inviterName}** (**{numInvites}** invites)` or `!config leaveMessage {memberName} **left**; Invited by **{inviterName}**`.
The following placeholders are available:

|                          | join | leave | example   | description                                                                             |
|--------------------------|------|-------|-----------|-----------------------------------------------------------------------------------------|
| {memberName}    				 | yes  | yes   | Andy      | The name of the member that just joined your discord server                             |
| {memberMention} 				 | yes  | no    | @Andy     | The mention of the member that just joined your discord server (person will be pinged). |
| {memberImage}   				 | yes  | yes   | [URL]     | URL of the avatar of the member                                                         |
| {inviterName}    				 | yes  | yes   | Andy      | The name of the inviter                                                                 |
| {inviterMention} 				 | yes  | yes   | @Andy     | The mention of the inviter (person will be pinged)                                      |
| {inviterImage}  				 | yes  | yes   | [URL]     | URL of the avatar of the inviter                                                        |
| {numInvites}    				 | yes  | yes   | 12        | Number of invites the inviter has in total                                              |
| {numRegularInvites}      | yes  | yes   | 7         | Number of invites the inviter has through regular invites                               |
| {numBonusInvites}  		   | yes  | yes   | 5         | Number of invites the inviter has as a bonus (they were assigned manually)              |
| {memberCount}  				   | yes  | yes   | 42        | Number of members your server has in total                                              |
| {numJoins}   						 | yes  | yes   | 3         | Number of times the user has joined the server                                          |
| {channelName}   				 | yes  | yes   | general       | The name of the channel where the invite code was created                           |
| {channelMention}         | yes  | yes   | #general      | Mention of the channel where the invite code was created                            |
| {inviteCode}             | yes  | yes   | fgSr30s       | Invite code used                                                                    |
| {memberCreated:date}     | yes  | yes   | 25.09.2016    | Date the discord user was created                                                   |
| {memberCreated:duration} | yes  | yes   | 5 weeks       | Duration since the discord user was created                                         |
| {memberCreated:timeAgo}  | yes  | yes   | 2 day ago     | Time the discord user was created                                                   |
| {firstJoin:date}    		 | yes  | yes   | 11.12.2017    | Date the user joined the server for the first time                                  |
| {firstJoin:duration}     | yes  | yes   | 4 days        | Duration since the user joined the server for the first time                        |
| {firstJoin:timeAgo}  	   | yes  | yes   | 1 week ago    | Time the user joined the server for the first time                                  |
| {previousJoin:date}  	   | yes  | no    | 02.04.2018    | Date when the user joined the server the last time                                  |
| {previousJoin:duration}  | yes  | no    | 2 months      | Duration since when the user joined the server the last time                        |
| {previousJoin:timeAgo}   | yes  | no    | 1 second ago  | Time when the user joined the server the last time                                  |
| {joinedAt:date}   			 | no   | yes   | 17.05.2018    | Date when the user joined                                                           |
| {joinedAt:duration}  	   | no   | yes   | 3 minutes     | Duration since when the user joined                                                 |
| {joinedAt:timeAgo}    	 | no   | yes   | 2 minutes ago | Time when the user joined                                                           |

## What are "Ranks" and how can I use them?

Ranks are used to assign roles to people when they reach a certain amount of invites. For example. if you have a role called `@Beginner` and you want people who have 5 or more invites to be added to that role, you would have to create a rank for that like so: `!add-rank @Beginner 5 (and if you want a description here)`. As soon as someone has 5 invites, he will automatically be added to that role!

## How can I disable the bot in all but one/some channels?

Take away the read message permissions in the channels where you don't want the bot to reply.
