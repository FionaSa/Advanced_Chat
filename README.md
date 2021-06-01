<div align="center">
  
![](https://media.discordapp.net/attachments/465937031600537600/770810281550413864/acc.png)

A simple **chat manager** plugin !

**Usages:**

**Anti - Flood**
  
 When someone flood a character, it delete its message and send this :

![](https://i.imgur.com/wnoBbu4.gif)

**Clear-chat:**

Clear all the chat

![](https://i.imgur.com/NNtpuaZ.gif)


**Anti-Swear:**
  
Execute a command when someone write a swear config in the swear.yml ( it delete the message sent)
  
YOU NEED PLACEHOLDER API -2.10.6 +

**Disable chat:**
  
**/ac disable **:so no-one can write on the chat
  
**/ac enable**: to enable it again



![](https://camo.githubusercontent.com/5508265574f2a3a98d013e58203bc9aa156d644e/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3436353933373033313630303533373630302f3737303831303330313235313035393736322f636f6d6d616e64732e706e67)

 **COMMANDS**

**/ac reload** - Reload the plugin; advancedchat.admin

**/ac help** - Show the help page; advancedchat.admin

**/ac clear** - Clear the chat; advancedchat.admin OR advancedchat.clear

**/ac clear <player_name>** - Clear the player chat; advancedchat.admin OR advancedchat.clear

**/ac disable/enable** - Disable or Enable the chat; advancedchat.admin OR advancedchat.chat
  
explanation: (command) - (description);(permission)


![](https://camo.githubusercontent.com/3549092fc54e6cfd7cda0e0f556af2093d2c4252/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3436353933373033313630303533373630302f3737303831303332333734393137353332372f7065726d732e706e67)

**PERMISSIONS**
  
advancedchat.admin (bypass anti flood, can clear the chat)

advancedchat.bypass.flood (bypass anti-flood)

advancedchat.bypass.clear (bypass clear chat)

advancedchat.bypass.swear (bypass anti-swear)

advancedchat.clear (clear the chat)

advancedchat.chat (enable/disable the chat)

**CONFIG.YML**


anti-flood: true
  
clear-chat: true
  
anti-swear: true
  
disable-chat: true

language: "french"

max-repetition: 5


**ENGLISH.YML**

prefix: "&f[&bAdvancedChat&f]"
  
no-permission: "&4You don't have the permission to do that"
  
no-args: "&4You've missed some args"
  
config-reload: "&bConfig reloaded successfully"
  
no-spam: "&bPlease, don't spam"
  
help: "&b&m-----&r&f&m-----&r&8[&bAdvanced&fChat&8]&f&m-----&r&b&m-----&r"
  
help-reload: "&b/ac reload &8- &fReload the plugin"
  
help-help: "&b/ac help &8- &fShow this page"
  
help-global-clear: "&b/ac clear &8- &fClear Global chat"
  
help-private-clear: "&b/ac clear <player> &8- &fClear player chat"
  
help-enable-chat: "&b/ac enable &8- &fEnable the chat"
  
help-disable-chat: "&b/ac disable &8- &fDisable the chat"
  
help-end: "&b&m-----&r&f&m-----&r&8 Page 1/1 &f&m-----&r&b&m-----&r"
  
message-clear: "&bYou have cleared the chat"


error-clear-chat-player: "&bThe player doesn't exists"

#Message sent to the player who disabled the chat

message-disable-chat: "&4Chat disabled"
  
message-enable-chat: "&bChat enabled"

#Error message if you don't have enabled the disable-chat

error-disable-chat: "&bYou don't have allowed disabling the chat, you can change it in the config.yml"

#Message sent to the player who try to write

message-disabled-chat-player: "&4Chat disabled"

**SWEAR.YML**

#You need to separate with the coma

swear: "swear1,swear2"


#The command used to mute the player
  
#use %player_name%

command-mute: "cmd %player_name%"


![](https://media.discordapp.net/attachments/712645831270072340/771003055386787840/ab88671aa7e80b755c75ce6416b370ae_icon.png)(https://discord.gg/V2AaQgc)

![](https://bstats.org/signatures/bukkit/advancedchat1.svg)
