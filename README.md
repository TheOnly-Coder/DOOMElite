# DOOM Elite

Play id Software's classic DOOM (1993) directly in your browser, compiled to WebAssembly.

## How to Play

1. Visit the [GitHub Pages site](https://theonly-coder.github.io/DOOMElite/)
2. Upload a DOOM WAD file (DOOM1.WAD shareware, DOOM.WAD, DOOM2.WAD, etc.)
3. Click **LAUNCH DOOM**
4. Click the game canvas to focus, then use keyboard to play

## Controls

| Key | Action |
|-----|--------|
| W/A/S/D or Arrow Keys | Move |
| Mouse Click | Fire |
| Space | Use / Open doors |
| 1-7 | Switch weapons |
| Shift | Run |
| Tab | Automap |
| Escape | Menu |
| Enter | Confirm |

## Technical Details

- Original DOOM source code (id Software, 1997 release) compiled with [Emscripten](https://emscripten.org/) to WebAssembly
- Runs at native DOOM resolution (320x200) scaled to HTML5 Canvas
- Sound is currently stubbed (visual-only port)
- Keyboard input via Emscripten HTML5 event callbacks

## WAD Files

- **DOOM1.WAD** (Shareware): Freely available, includes Episode 1
- **DOOM.WAD** (Registered/Ultimate): Requires original purchase
- **DOOM2.WAD**: Requires original purchase

## License

DOOM source code is released under the DOOM Source Code License by id Software.
All original DOOM game content remains property of id Software / ZeniMax Media.
