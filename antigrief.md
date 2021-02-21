# Security Bot | Anti Grief Documentation

This is Security Bot's official guide on how to properly use Anti Grief.
Its important to note that this system is still a work in progress, and will continue to be updated.
If you find any bugs please contact ry#1000 on Discord.

## Description of Anti Grief
Anti Grief is a system developed for Security Bot to prevent nuking / griefing of your server through 
automated mass commands like; mass ban, mass delete. At this moment, the only configuration settings 
that are open to you are mass ban and mass delete, both systems that are triggered will result in a ban
for the invoker.

## How to use Anti Grief
Anti Grief is a server-owner-only command and can be only controlled by the guild owner.
The only person exempt from punishment from Anti Grief is the server owner.

To properly use Security's Anti Grief, youll have to set your logchannel, time, and limit.

Lastly, toggle once you've finished the configuration process.

```
+help antigrief
```

### AntiGrief Limit

The subcommand limit would be for setting up the threshold for bans.
If a user bans passed the amount that you set, Security bans them.

```
+antigrief limit <massban/massdelete> <amount>
```
The threshold in this case would be the limit that has to be passed for the antigrief to work.

Example: 
```
+antigrief limit massdelete 5
```
A threshold of 5 bans would have to be passed for the trigger system to function. 
After the 5th ban, the invoker will be banned from the server for flagging the anti grief system.


### AntiGrief Time

The subcommand time would be for setting the time that the invoker has to trigger to be punished.
If a user bans X amount of users in under Y amount of time, Security bans them.

```
+antigrief time <massban/massdelete> <time>
```





















