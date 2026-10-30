# XMPLAY v2.0

XM (FastTracker II) player for the MSX turboR with an OPL4 (MoonSound / Shockwave, up to 2 MB sample RAM), running under MSX-DOS2 / Nextor.

Vibecoded by Latok using Grok Bot version 1.17.0

## Features
- Up to 32 XM channels on the 24 OPL4 voices with dynamic voice allocation (a new note takes the quietest or releasing voice when all are busy)
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
- `AQUABABE.XM` (18 channels)
- `ADAY.XM` ("A day without her", 28 channels)

The example songs are the work of their original authors and are included for testing only.
