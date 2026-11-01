# Odysseus: Shadow of Ithaca

A standalone 2D arcade fighter built with Canvas, CSS, and Web Audio. The entire game runs from `index.html`; no build step or asset downloads are required.

## Play

Open `index.html` in a modern browser and choose **Start Fight**. The game requests fullscreen when a match begins. Choose a Greek arena, fighter, outfit, personality, and weapon first. Use **EN / IT** to switch the menu between English and Italian. The **About** tab includes the creator profile link and embedded page.

## Fighters and arenas

Select from Odysseus, Achilles, Hector, Atalanta, Tommy Vercetti, Trevor Phillips, Goku, Ben 10, Ryu, or Kage. The game draws its character designs and animation in Canvas 2D.

Fight in Ithaca, Sparta, Troy, and Sicily, or revisit the bonus stages: China’s Dragon Tower, India’s Vidhana Soudha, the USA Main Event Dome, Dubai’s Burj Afterdark, Tokyo’s Neon Crossing, and London’s Clocktower Bridge.

## Controls

- **A / D:** move; **W:** jump; **S:** crouch; **I:** guard
- **O:** punch; **P:** kick; **Q:** weapon strike
- On phones, rotate to landscape. Use the round movement pad on the left and the punch, kick, and weapon buttons on the right.
- **Esc:** pause or resume

Punches, kicks, and weapon strikes use active hit frames and collision checks. Strong hits can knock fighters down; they fall, recover, and get back up. The AI opponent gets a larger health bar and stronger damage in boss rounds every third round.

## Score, coins, and weapons

Survive rounds to earn coins and score. Your wallet, highest score, and round record save in the browser.

- **Katana:** included
- **Naginata:** unlock for 120 coins
- **Twin blades:** unlock for 250 coins

## Music

Choose **Load MP3** and select the `Ninja in the Night` theme from your device. It plays during fights and stops between rounds. The file stays on your device and must be selected again in a new browser session. Built-in synthesized music and hit sounds play when no MP3 is loaded.

## Deploy

This is a static single-page game. Deploy the project folder to Vercel with the root directory set to the folder containing `index.html`; no build command or output directory is needed.
