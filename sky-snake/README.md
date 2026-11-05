# SKY SNAKE — Turbo Flight

A browser-based 3D flying snake game with third-person camera, obstacles, checkpoint rings, turbo acceleration, and an optional music track.

## Play

Open [the game](./index.html) in a browser or use GitHub Pages at https://nestlys.github.io/Programms/sky-snake/.

## Controls

| Key | Action |
| --- | --- |
| W / S | Ascend / Descend |
| A / D | Turn left / right |
| Shift (hold) | Accelerate (9.2 → 19 m/s) |
| P or Esc | Pause |

### Music

The interface includes an on/off button and a volume slider. Initial volume is **30%**, with a fade-in on Start and a fade-out on pause or collision. The song loops while playing.

**Audio setup:** This commit adds the playback controls, but the MP3 must be added separately at [`assets/the-jungle-witch.mp3`](./assets/the-jungle-witch.mp3) for it to work on GitHub Pages. Upload the file at exactly that path using GitHub's **Add file → Upload files**, preserving the filename. The game itself works even when the file is absent.

For an offline playable copy containing the actual MP3, use the bundled ZIP or standalone HTML provided alongside the ChatGPT conversation.

### Track credit and license

**The Jungle Witch** — **vertigoaway (Vera Claire Vertigo)**. Original recording used without modification; only in-game playback volume is adjusted.

- Artist / source: https://vertigoaway.bandcamp.com/track/the-jungle-witch
- Creative Commons **Attribution–NonCommercial–ShareAlike 4.0 International**: https://creativecommons.org/licenses/by-nc-sa/4.0/
- Noncommercial uses and redistribution require proper attribution and compliance with the license. Do not use the recording in a commercial game without obtaining further permission. The track's license applies to the music, not automatically to all game code.

## Features

- Smooth third-person flight with flexible steering and a snake body following the traveled path.
- Collect crystals to increase length.
- Sky City bridge, buildings, and pillars, with collision detection.
- 7 checkpoint rings, lap counter and timer, adjusted for obstacle clearance.
- Predictive red warning near walls, ground and ceiling, including turbo mode.

This is a self-contained HTML5 Canvas prototype created collaboratively in ChatGPT.
