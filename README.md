# Gun Showdown

A 3D blocky shooter that runs in any web browser. Play solo against bots, or play **online with friends**. There's no server to install and it doesn't need Claude.

## Play
Turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root), then open:

`https://<your-username>.github.io/<repo-name>/`

## Online multiplayer
1. One person clicks **HOST ONLINE GAME**. They get a 5-letter room code and an invite link (click the room box at the top to copy it).
2. Friends open the link and click **JOIN ROOM**, or click **JOIN ONLINE GAME** and type the code.
3. Everyone picks a gun. Rounds last 3 minutes, and the most kills wins. A new round starts automatically.

The host's browser runs the match, so the host needs to keep their tab open. Connections are peer-to-peer (WebRTC through PeerJS). This works on most home networks. Some strict school or work networks block it.

## Controls
WASD move · Space jump · Mouse look (or arrow keys) · Click shoot · Hold right-click to aim · Q change quality · Esc pause
