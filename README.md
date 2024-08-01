# rutorrent-discord
A rutorrent plugin for discord webhook notifications (https://discordapp.com/developers/docs/resources/webhook)

Sends messages directly into a discord channel with configurable parameters:

![https://i.imgur.com/JMoa8H5.png](https://i.imgur.com/JMoa8H5.png)

And if discord is properly set up, displays desktop notifications the moment a torrent is added, deleted or finished:

![https://i.imgur.com/yXkpbU1.png](https://i.imgur.com/yXkpbU1.png)

# Install

* Make sure you have php-curl installed
* download/clone repo
* add discordpush to your rutorrent/plugins directory
* reload webinterface

# Usage

* go to settings > Discord
* Enable, tick what evens should be notified
* Paste webhook url you got from your respective channel settings where you want the notifications to appear
