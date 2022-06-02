![Logo](https://www.seekpng.com/png/full/270-2700588_vip-tickets-for-trixie-delight-u0026-starship-vip.png)

<div align="center">
  
<br>![Windows](https://github.com/danielkrupinski/Osiris/workflows/Windows/badge.svg?branch=master&event=push)
[![PayPal](https://img.shields.io/badge/donate-PayPal-104098.svg?style=plastic&logo=PayPal)](https://paypal.me/kasai772)
  
  </div>
  
  # Features
  * **Watch my YT video & host your**
- Setup 
- Open 
- Close
- Add
- Remove
- Rename
- Close
- Reopen
- Per Server Prefix 
- Ping Command

# 💎 Preview
## This it what the bot looks like...
![](https://github.com/mrmotchy/stuff/blob/main/Unben55555555555555annt.PNG?raw=true)

![](https://github.com/mrmotchy/stuff/blob/main/Unben6666666666annt.PNG?raw=true)

# 🔩 Installation
## Create [TOKEN](https://discord.com/developers/)
```
$ under bot_token
```

## Create [prefix]()
```
$ server prefixes could be -; +; !; ?;...
```

# 💻 Code example
This is a simple example of code using this package.

```js
            id: require('quick.db').fetch(`TicketAdminRole_${message.guild.id}`),
            allow: ["SEND_MESSAGES", "VIEW_CHANNEL"]
        }, {
            id: message.guild.roles.everyone,
            deny: ["VIEW_CHANNEL"]
        }]).then(() => {
            message.channel.send({
                embed: {
                    title: '✅ | Done',
                    description: `${txt} has been added to this ticket`,
                    color: 0x00D700
                }
            }).then(async function(msg) {
                setTimeout(() => {
                    msg.delete().catch(err => { return })
                }, 1000 * 7);
```
&
```js
                const embed2 = new Discord.MessageEmbed()
                .setTitle(`Premium Ticket Commands`)
                .setThumbnail(message.guild.iconURL({ dynamic: true }))
                .setDescription(`**__Here Are My Commands:__**\n\`setup,\` \`transcript,\` \`rename,\` \`remove,\` \`ping,\` \`open,\` \`close\``)
                .setColor(`#0x2F3136`)
```

<br/>



## Installation
