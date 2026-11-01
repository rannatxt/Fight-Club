# Moonlit Rumble — Fight Club 16

A standalone, pixel-art rooftop fighting game made with Canvas 2D and procedural Web Audio. The game runs directly in a modern browser; it has no build step, libraries, image downloads, or other external assets.

## Play

Open `index.html` in a browser. A match begins after the short round intro. Press a key, tap the screen, or use a touch button to enable sound. On mobile, the touch controls appear automatically. Use **Options** to change match mode, CPU difficulty, audio levels, touch controls, and hitbox display.

## Controls

| Player | Move | Light | Heavy | Special | Guard |
| --- | --- | --- | --- | --- | --- |
| Player 1 | WASD | J | K | L | I |
| Player 2 | Arrow keys | Numpad 1 | Numpad 2 | Numpad 3 | Shift |

Choose **Local 2P** in Options to play against another person. The CPU option supports Easy and Hard difficulty.

## Included

- Fixed-step 60 Hz simulation with independent animation rendering.
- A layered moonlit temple rooftop, tiled wooden floor, parallax clouds, and custom pixel fighters drawn in the canvas.
- Fighter state machines, jump physics, boundaries, active attack frames, AABB hit and hurt boxes, blocking, damage, stun, knockback, hit-stop, sparks, projectiles, rounds, combos, scores, and a 99-second timer.
- Responsive arcade HUD and a chrome-styled control deck.
- Synthesized chiptune music, percussion, and combat sound effects using Web Audio.
- Optional touch controls and hitbox visualization.
