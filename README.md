# Group Chat extension

Goal was to use a socket extension to communicate realtime with people - anyonee with the extension open can identify them selves . and chat.

1. I was able to prompt . user to set a username

![groupchat1](groupchat1.png)

2. Once connected, set an online status

![groupchat2](groupchat2.png)

3. Have a socket server running on a cloud server. Server.js is being served on a droplet in digitalocean so this extension can be served digitally. In content.js there is an IP address, which is the address of digitalocean. A copy of server.js is sitting there on digital ocean. Using this extension as many users can join this group chat. 

![groupchat3](groupchat3.png)

4. Enabling a second user connect from another pc

![groupchat4](groupchat4.png)

5. This interaction is fairly straight forward in a standard broswer setting but i encountered issues getting it done as an extension; like limitations in getting multiple javascript libraries (jQuery, Socket) to operate in content.js. The only problem is the message is not being sent multiple people in a group can connect, i.e. a connection is there but messages are not functional.
