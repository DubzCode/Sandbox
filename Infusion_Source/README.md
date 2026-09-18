# Infusion

A 60-second browser survival game where defeating enemies restores color to a grayscale world.

## Run the game

Open `index.html` in a browser. For the most reliable local setup, serve this folder with a small web server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Controls

- WASD or arrow keys: Move
- Mouse: Aim
- Attacks fire automatically
- Sound button: Toggle audio

## Files

- `index.html`: Game interface and canvas
- `style.css`: Layout and visual styling
- `game.js`: Game loop, combat, enemies, powers, scoring, and effects
