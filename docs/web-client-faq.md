FAQ Web Client for Encounter Plus

# How does the Web Client work?
The device that is running the game can act as a server for other players to connect to either locally or over the internet. Just go into the external display setting located in the top left of E+ and turn it on.

### Why doesn’t the URL E+ gives me work?
**There are two parts to this question.**
1. Part one: you need to **open port 8080 on your router** for the IP address E+ is displaying. That needs to be done on your router. **Please refer to your routers user manual** or https://portforward.com for information on how to change port settings.
2. Part two: **There are two URLs** that Encounter Plus gives your for remote play. One is for local play and one is for remtoe play. **To play remotely requires the "Public Access" URL.** Tapping on the "Public Access" button will show you the URL and it will look like this: http://client.encounter.plus?remoteHost=[your IP Address Here]:8080. This will be the URL to give to you players to remote into your server. 

*Note: IPv6 support has been recently added. So if your ISP provides this type of IP address, make sure you havce updated to the latest version of Encounter Plus.

### I opened the port and got my IP address, but it still says Websocket Disconnected when players try to join.
This can happen when **browsers automatically redirect to https://client.encounter.plus instead of http://client.encounter.plus.** Try turning on **incognito mode in Chrome or Private Browsing in Safari** to keep it from redirecting. If your browser is still redirecting to https, **try clearing your browser history.** 

**Note: Currently, only Safari and Chrome have been tested for the E+ Web Client.** 

### All or some of my tokens aren't appearing on the web client.
**Try moving the tokens around to refresh them** on the web client side. Also **try re-placing the tokens**, this can be done by dragging them in from the initiative list or double tapping on the map and pressing `place create`/`place party`. If that doens't work, **try turning off web server in E+ and turning it back on.** Once this is done **have the players reconnect.** 

### What are the different settings in the web server section of E+?
Those allow the DM to control how many people can interact with the tokens onscreen at any given point. When it is set to **All**, then anyone can move tokens at anytime. Setting it to **Turn Only** will only allow tokens to move on their turn. Setting it to **None** will only allow the DM to move tokens. 

### Known Issues

There is no way to kick players from the server. 

Password Protection for individual games coming soon. 

Tokens have the ability to move through walls, unless you enable restricted movement ![Restricted Movement Icon](https://help.encounter.plus/icons/move-restricted2.png "Restricted Movement"), so be careful when moving them. 

Auras and other animated assets are currently not working. Stay Tuned. 

Markers added in the DM layer will not be visible to players. However, anything written with the pen or highlighter tool will be visible even if added in the DM layer. 

