# XMPLAY v1.0

XM (FastTracker II) player for the MSX turboR with an OPL4 (MoonSound / Shockwave, up to 2 MB sample RAM), running under MSX-DOS2 / Nextor.

Vibecoded by Latok using Grok Bot version 1.17.0

## Features
- Up to 32 XM channels: 23 OPL4 hardware voices, extra channels software-mixed (8-bit mono, R800) into one ring voice
- Long samples (>64K) played without sample-RAM writes during playback
- Volume/panning envelopes, fadeout, auto-vibrato, nearly all XM effects
- Load progress bar, info screen, OPL4 RAM detection, 256 KB turboR support

## Usage
```
XMPLAY song.xm      play once, return to DOS at the end
XMPLAY song.xm /l   loop the song
```
ESC quits at any time.

## Example songs
- `AQUABABE.XM` (18 channels, hardware voices only)
- `ADAY.XM` ("A day without her", 28 channels, uses the mixer)

The example songs are the work of their original authors and are included for testing only.
