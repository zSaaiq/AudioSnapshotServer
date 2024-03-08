# AudioSnapshotServer

*Where do you get the audio data for your visualizer? I pull it out of my AudioSnapshotServer.*

A modified verison of Nepeta's ASS, which is a TCP/IP server to fetch audio buffer's snapshot from mediaserverd.

## Installation

**iOS 15.0-16.6.1 required.**

**This tweak by itself does nothing noticeable. A client tweak is neccessary for visible effects - try [Mitsuha Forever](https://zsaaiq.github.io/jailbreakrepo/)**

1. Add this repository to sileo or zebra: https://zsaaiq.github.io/jailbreakrepo/.
2. Install AudioSnapshotServer and libmitsuhaforever in order to use Mitsuha Forever.

## How to use it in your tweak?

If you send anything to localhost at the port 44333 it will reply with a dump of the current audio buffer (raw PCM audio data). That's all to it.
