# steem.craft
STEEM.CRAFT is a plugin for Bukkit/Spigot, which allows players to interact with the STEEM Blockchain within Minecraft.
Server owners can create custom comments, which are later executable by a command. Plugin developers can also use the included api to broadcast custom comments as connected user or the server.

## Setup
Compile the plugin.
To get this plugin running, a STEEM Wallet is needed. In the best case this is a dedicated STEEM Wallet for the minecraft server.
Run your minecraft server and let the plugin generate the config.yml file.
Enter steem_username and steem_private_posting in the config.yml, be sure to not use the public, active or master key.
Add Comments and the content, there is already a example post to guide you, you can execute it with /steemcraft execute example this is a comment text
By restarting the server, STEEM.CRAFT is ready to use and is going to post by using ingame commands.
To let users also vote and comment, they have to give a authentification to your STEEM Wallet. 
After that, your dedicated STEEM Wallet can cast votes and broadcast new comments with the existing private posting key in the name of the user.
A easy way to do this is using SteemConnect: https://steemconnect.com/authorize/@<your dedicated minecraft server steem wallet name>

## Todo
Everything is currently written in Skript. The plan is to rewrite everything in Java for better performance and doing the whole process directly on the server.

## Links
You can visit steem.craft on steemit.com, a dapp for the STEEM Blockchain.
* [steem.craft](https://steemit.com/@steem.craft) on Steemit

## Developer
Currently, STEEM.CRAFT is developed by:
* [abwasserrohr](https://github.com/abwasserrohr) (Developer)
