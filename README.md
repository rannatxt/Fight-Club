# Odysseus: Shadow of Ithaca

A full-screen, single-player 2D arena fighter built with Canvas 2D, CSS, and Web Audio. It runs as a lightweight static site with no framework or build step.

## Run locally

Serve the project folder with any static web server. For Python, run `py -m http.server 8000` from this folder, then open `http://localhost:8000`.

Choose **Start Fight** to enter fullscreen. Pick an arena, fighter, outfit, temperament, and weapon first. Your profile, coins, and records save in the browser.

## Controls

- **A / D:** move; **W:** jump; **S:** crouch; **I:** block
- **O:** punch; **P:** kick; **Q:** weapon strike
- **Esc:** pause or resume
- On phones, rotate to landscape. Use the movement pad and the round attack buttons.

Attacks have active frames and collision checks, with hit-stop, impact sparks, knockback, blocking, and knockdown recovery. A CPU rival grows stronger across the survival rounds, including a boss encounter every third round.

## Fighters and arenas

Choose Odysseus, Achilles, Hector, Atalanta, Tommy Vercetti, Trevor Phillips, Goku, Ben 10, Ryu, or Kage. The game draws smooth shaded 2D characters and animated poses directly in Canvas. The presentation is stylized 2D artwork rather than photoreal captured humans.

Arenas include Ithaca, Sparta, Troy, Sicily, Dragon Tower, Vidhana Soudha, Main Event Dome, Burj Afterdark, Neon Crossing, and Clocktower Bridge.

## Music

Use **Load MP3** to select a locally stored theme for fights. The selected file stays on the device and needs to be selected again in a new browser session. Procedural Web Audio music and sound effects are available without a music file.

## Project files

- `index.html` — page structure and game HUD
- `styles.css` — responsive fullscreen UI and touch controls
- `src/game.js` — Canvas rendering, animation, physics, combat, audio, and game state

## Deploy

This is a static site. Import the repository into Vercel with the project root set to this folder. No install or build command is required; serve the repository root as the output.
