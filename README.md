<p align="center">
<img src="https://user-images.githubusercontent.com/21063304/211214783-90d24fac-ecc5-4eb0-802e-52a5ba26610a.png"/>
</p>




<h4 align="center">Author: https://github.com/SubZero0</h4>
<h4 align="center">API: https://dev.bukkit.org/projects/legendchat/pages/api</h4>


<h1>Introduction​</h1>
<p style="font-size: 5px">
A new channel-based chat plugin with high compatibility with other plugin's tags and an awesome API for developers! Do you use Herochat but has found some really boring imperfections? Why don't you try to use Legendchat?
For server owners: you will have the same design as herochat and your players won't notice the difference! And you can create a channel only for BungeeCord communication! Check our BungeeCord page!
For developers: want to add a new prefix, suffix or remove some people from receiving a message without removing others? Nice! We have an easy to use API! Check our API page!
</p>

​
<h3>[!] > COMPATIBLE WITH 1.19! < [!]</h3>
​

<h1>Main features</h1>
<p style="font-size: 5px">
Configurable chat channels (delay to send messages, cost ($) to send messages etc).
Temporary channels (with permissions)
Permissions to almost everything.
Quick message (ex.: /g <message>).
Private messages (/tell).
Compatible with almost every chat tag.
Update checker (can be disabled, see Plugin configuration)
</p>

<h1>Commands​</h1>
<p style="font-size: 5px">
List all available commands in the plugin.
Command - Description
</p>
<ul>
<li>/legendchat - Display LegendChat Help
<li>/channel <channel> - Focus in other channel
<li>/tempchannel - Temporary channel command
<li>/tell <player>[message] - Send a private message or start a chat
<li>/reply <player> <message> - Reply a private message
<li>/afk - AFK mode (block private messages)
<li>/ignore <player> - Ignore player messages and private messages
<li>/mute <channel> - Ignore channel messages
<p style="font-size: 5px">
NOTICE:
</p>
<li>/legendchat = /lc
<li>/channel = /ch
<li>/tempchannel = /tc
<li>/tell = /t = /pm = /msg
<li>/reply = /r
</ul>

<h1>Permissions​</h1>
<details>
  <summary>Spoiler</summary>
    <p style="font-size: 5px">
    Permission - Description
    </p>
    <ul>
        <li>legendchat.channel.<channel>.chat - Permission to read and write in the channel
        <li>legendchat.channel.<channel>.focus - Permission to focus () in the channel
        <li>legendchat.channel.<channel>.free - Permission to bypass message cost in the channel
        <li>legendchat.channel.<channel>.nodelay - Permission to send messages without delay in the channel
        <li>legendchat.channel.<channel>.blockwrite - Permission to block writing in the channel
        <li>legendchat.channel.<channel>.blockmute - Permission to block muting the channel (NEW - V1.1.2)
        <li>legendchat.tempchannel.manager - Permission to create and delete temporary channels
        <li>legendchat.tempchannel.color - Permissions to change your temporary channel color
        <li>legendchat.tempchannel.user - Permission to join and leave temporary channels
        <li>legendchat.color.<color> - Permission to use certain colors or formats in channels
        <li>legendchat.color.allcolors - Permission to all colors in channels
        <li>legendchat.color.allformats - Permission to use all formats in channels
        <li>legendchat.block.tell - Permission to block player from sending private messages
        <li>legendchat.block.locktell - Permission to block player chat with /tell <player>
        <li>legendchat.block.reply - Permission to block reply private messages
        <li>legendchat.block.afk - Permission to block using /afk
        <li>legendchat.block.afkmotive - Permission to block player from setting an afk message
        <li>legendchat.block.ignore - Permission to block player from being ignored
        <li>legendchat.admin - Admin permission, unlock everything
        <li>legendchat.admin.tempchannel - Permission to use: /lc deltc
        <li>legendchat.admin.playerch - Permission to use: /lc playerch
        <li>legendchat.admin.channel - Permission to use: /lc channel
        <li>legendchat.admin.spy - Permission to use: /lc spy
        <li>legendchat.admin.hide - Permission to use: /lc hide
        <li>legendchat.admin.mute - Permission to use: /lc mute
        <li>legendchat.admin.unmute - Permission to use: /lc unmute
        <li>legendchat.admin.muteall - Permission to use: /lc muteall
        <li>legendchat.admin.unmuteall - Permission to use: /lc unmuteall
        <li>legendchat.admin.reload - Permission to use: /lc reload
    </ul>
    <p style="font-size: 5px">
    <​channel​> = channel name in lowercase
    </p>
    <p style="font-size: 5px">
    <​color​> = color name (like blue) or format name (like bold) in lowercase
    </p>
</details>

<h1>Avaliable Channel Colors</h1>
<details>
  <summary>Spoiler</summary>
  <ul>
    <li>BLACK
    <li>DARKBLUE
    <li>DARGREEN
    <li>DARKAQUA
    <li>DARKRED
    <li>DARKPURPLE
    <li>GOLD
    <li>GRAY
    <li>DARKGRAY
    <li>BLUE
    <li>GREEN
    <li>AQUA
    <li>RED
    <li>LIGHTPURPLE
    <li>YELLOW
    <li>WHITE
    </ul>
</details>
