# AZ DeskShare

**by Art Midnight**

Show one PC's screen and sound on every PC in the office, over your local network. Picture and sound stay in step.

- **One Source PC, many Viewer PCs.** Viewers watch fullscreen, so they look just like the Source, or in a resizable window.
- **View only or Control.** Any Viewer can take over the Source's mouse and keyboard when needed, one PC at a time.
- **Choose where the sound plays** on each Viewer, such as a TV or the PC speakers.
- **Reconnects by itself** whenever the Source PC turns on.
- **No accounts, no sign-in.** Viewers pair once with the Source's pairing code.
- Up to **8K** when the Source PC's graphics card and the network allow it.

## Download
Get **AZDeskShare-Setup-x.y.z.exe** from the [Releases](../../releases) page, and run it on the Source PC and on every Viewer PC.

## Requirements
- Windows 10 (1809 or later) or Windows 11, 64-bit
- All PCs on the same local network. Wired gigabit Ethernet is recommended. Set the network to **Private** in Windows.
- Source PC: a recent graphics card (NVIDIA, AMD or Intel) for hardware video encoding. 4K and 8K need a newer GPU.

## Quick start
1. On the Source PC: install, choose **This is the Source PC**, create a pairing code, and approve the Windows prompt.
2. On each Viewer PC: install, choose **This is a Viewer PC**, pick the Source PC, type the pairing code, and press **Pair**.

That's it. Viewers connect by themselves from now on.

## Third-party software
AZ DeskShare runs [Sunshine](https://github.com/LizardByte/Sunshine) and [Moonlight](https://github.com/moonlight-stream/moonlight-qt) as its streaming engines. Both are open-source under the GNU GPL v3, and the notices are included with each release.
