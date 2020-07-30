# zoom-clone

## reference 
[WebDevSimplified/Zoom-Clone-With-WebRTC](https://github.com/WebDevSimplified/Zoom-Clone-With-WebRTC)

[webrtc with peerjs and socket.io](https://morioh.com/p/166cacd988d4?f=5c21fb01c16e2556b555ab32&fbclid=IwAR0D7fbspVxWkRcLRj28VSOV09pPO2UQTExe__-0g_f70CossXl2h8P2R9o)
## introduction

This is a small project for 

use socket.io and peer.js to create webrtc video talk

## prerequest

peer.js install

[peer js](https://peerjs.com/docs.html)

for peer js server

```shell
npm i -g peer
```
start peerjs server on port 3001
```shell
peerjs --port 3001
```
use peer server to generate peerId 
for each one to join the page

and simply the webrtc create process

## socket.io

use socket.io to broadcast  user when user join the same roomId

and send disconnect message for use to user  disonnect 