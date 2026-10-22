# RNG Editor

Edit video by describing it. RNG Editor is a desktop app: you pick your footage, choose a style and write what
you want. Claude cuts, captions, adds music and renders it with the RNG editing engine. You watch the result, leave
comments at any moment and send them back, and the next version appears.

**Download:** see [Releases](https://github.com/AndreRNG/rng-editor/releases) or https://www.rng.media/editor

## Requirements
- Linux, 64-bit (Mac and Windows are coming)
- A Claude account and [Claude Code](https://claude.ai/code)
- An NVIDIA GPU is strongly recommended (transcription and encoding use it)
- About 10 GB free for the engine's tools and speech model, installed once on first launch

## Install
Download the `.AppImage`, make it executable and open it:
```bash
chmod +x rng-editor-*-linux-x64.AppImage
./rng-editor-*-linux-x64.AppImage
```
If it doesn't start, install FUSE 2 (`libfuse2` on Debian/Ubuntu, `fuse2` on Arch).

## Privacy
Everything stays on your computer. Your footage, edits, comments and conversations are between you and your own
Claude account. RNG Editor has no analytics and collects nothing. If you report a problem, you see the whole
report first and send it yourself from your own email app.

This repository holds releases only.

© RNG Media S.L.
