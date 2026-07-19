# 🦖 Bevz Runner

A browser-based endless runner starring **Bevz**, Bevzilla's mascot — inspired by the Chrome dino game, fully reskinned with the Bevzilla brand.

## How to play
- **Best played in landscape** — on phones you'll be prompted to rotate your device before the run starts
- **Jump:** Space / Up Arrow / tap the canvas / on-screen Jump button
- **Duck:** Down Arrow / swipe down on the canvas / on-screen Duck button
- Jump over coffee cups and paper stacks
- Duck under grumpy clouds
- Collect 🪙 **Dino Coins** for score
- Collect 5 ☕ **coffee beans** to trigger a **Brew Boost** (temporary invincibility)
- Run through four scenes that cycle as your score climbs: The Office, Campus, Downtown, The Café

## What's new
- **Global leaderboard** — the top 5 scores are now shared across every player, not just saved on one device. Beat a high score and your initials go up for everyone. (If the file is ever downloaded and opened outside Claude, it falls back to a local device-only leaderboard automatically.)
- **Landscape mode** — the game locks to landscape on mobile, with a rotate prompt if you're holding your phone upright.
- **Bevz redesign** — the runner sprite now matches the brand sheet: blunt friendly snout, round-cornered signature shades, yellow spikes, cream belly, and his coffee mug in hand.

## Run it locally
Just open `index.html` in any browser — no build step, no dependencies.

## Host it free on GitHub Pages
1. Create a new GitHub repository (e.g. `bevz-runner`)
2. Upload `index.html` to the repo (drag-and-drop on github.com works fine)
3. Go to **Settings → Pages**
4. Under "Build and deployment", set **Source: Deploy from a branch**
5. Choose branch `main`, folder `/ (root)`, then **Save**
6. Wait ~1 minute — your game will be live at:
   `https://<your-username>.github.io/bevz-runner/`

That link is shareable and embeddable (e.g. in an `<iframe>` on Instagram bio-link pages, Discord, or your Canva deck as a QR code).

## Customizing
Everything is in one file (`index.html`) — colors, obstacle types, and text are near the top of the `<style>` and `<script>` sections if you want to tweak brand colors, difficulty, or add new obstacle art. The Bevz sprite itself lives in the `drawBevz()` function.
