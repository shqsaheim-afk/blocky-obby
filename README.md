# Blocky Obby

A 3D blocky obby game with voice and video calling between players.

**Play:** https://shqsaheim-afk.github.io/blocky-obby/

## How the video calls work
- Open the same link on both devices, create an account, then add each other in **Friends**.
- Calls connect peer to peer through PeerJS, so both players need the page open.
- The page must be served over HTTPS (GitHub Pages is) for the camera and microphone to work.
- The account named `youtube` is a host account: it can add any username, creating the account
  if it does not exist, and the friendship is accepted automatically.

## Updating the game
Replace `index.html` in this repo. GitHub Pages redeploys automatically within a minute.

Single self-contained file: three.js and PeerJS load from CDNs, everything else is inline.
