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

You'll notice upon setting up the system that you're open to configuring your limits and time.

```
+help antigrief
```

The subcommand limit would be for setting up the threshold. 

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














