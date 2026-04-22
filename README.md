# 🎹 Piano Learn

Visual piano learning in your browser. Upload a MusicXML sheet music file and watch the notes fall onto a piano keyboard labeled with **do re mi** (or 简谱 / C D E). Practice one hand at a time, slow the tempo down, and follow the real score alongside the falling notes.

## Features

- 📄 Upload `.xml`, `.musicxml`, or `.mxl` files
- 🎼 Real sheet music rendered on screen (highlights the current note as it plays)
- 🎵 Falling-notes visualization — red = right hand, blue = left hand
- 🐢 Speed control (20%–150%) for slowing down hard passages
- 🖐️ Hand filter — practice left only, right only, or both
- 🏷️ Key labels: `do re mi`, `1 2 3` (简谱), `C D E`, or none
- 🎹 Salamander Grand Piano samples (real piano sound, not synth)
- ⌨️ Space = play/pause · click any key to try it

## Try it

**🌐 Live demo: https://nina123123.github.io/piano-learn/**

Or run locally: just open `index.html` in any modern browser — no build step, no server required.

## Where to find MusicXML files

- [MuseScore.com](https://musescore.com) — huge user-uploaded library
- [IMSLP](https://imslp.org) — classical pieces, public domain
- [MuseScore desktop app](https://musescore.org) — free; can export any score to MusicXML

## Credits

- [Verovio](https://www.verovio.org/) — music notation engraving
- [Tone.js](https://tonejs.github.io/) — Web Audio playback
- [@tonejs/midi](https://github.com/Tonejs/Midi) — MIDI parsing
- [Salamander Grand Piano](https://archive.org/details/SalamanderGrandPianoV3) — piano samples
