# <picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PeerPigeon/PeerPigeon/main/assets/pigeonlogo-dark.svg"><img src="https://raw.githubusercontent.com/PeerPigeon/PeerPigeon/main/assets/pigeonlogo.svg" alt="" height="36" align="top"></picture> PeerPigeon

*Peer-to-peer apps, and the open stack they run on.*

Apps that run between people's own devices, not on a company's servers.<br>
Browsers link into a mesh over WebRTC, relays only introduce them, and storage servers anyone can run keep what
matters while nobody is online.

## Apps

| App | |
| --- | --- |
| [PigeonChess](https://chess.peer.ooo) | Chess between two browsers, with tournaments, spectators and PigeonAI to play against |
| [PigeonFeed](https://feed.peer.ooo) | Posts, pictures, friends and messages, kept on the mesh |
| [PigeonAI](https://docs.peerpigeon.io/apps/pigeonai) | Language models run by peers, for anyone in the room to ask |

Sign in once, with PigeonIdP, for all of them.

## Building blocks

| Block | |
| --- | --- |
| [PeerPigeon](https://github.com/PeerPigeon/PeerPigeon) | The mesh: messages, encryption and signed storage, in browsers and Node |
| [FreeRTC](https://github.com/draeder/freertc) | Relays that introduce peers and federate with each other, on Workers or Node |
| [PigeonFS](https://github.com/PeerPigeon/PigeonFS) | Storage servers anyone can run, for rooms, records and file pieces |
| [PigeonIdP](https://github.com/PeerPigeon/PigeonIdP) | Accounts without a company: one name everywhere, your own keys |
| [UnSea](https://github.com/draeder/unsea) | Keys, signatures and encryption in plain JavaScript |
| [wurl](https://github.com/draeder/wurl) | curl for WebRTC: join any relay as a peer from the command line |

```
npm install peerpigeon
```

## Specifications

| Spec | |
| --- | --- |
| [PSP](https://docs.peerpigeon.io/blocks/psp) | The Peer Signaling Protocol, which the relays speak (v1.0, revision 3) |
| [CECR](https://docs.peerpigeon.io/blocks/cecr) | Convergent Extremal Coordinate Routing: how a message crosses a partly connected mesh |

## Run your own

A [relay](https://docs.peerpigeon.io/run/relay), a [storage server](https://docs.peerpigeon.io/run/storage-server),
or the whole [stack](https://docs.peerpigeon.io/run/pigeonstack) on one machine. The
[console](https://console.peerpigeon.io) shows them, and the people in your apps.

## Links

[peerpigeon.io](https://peerpigeon.io) · [Docs](https://docs.peerpigeon.io) · [peer.ooo](https://peer.ooo) · [Demo](https://pigeon.peer.ooo) · [npm](https://www.npmjs.com/package/peerpigeon)
