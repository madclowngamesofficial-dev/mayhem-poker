# Mystery Crate Poker

First-person Texas Hold'em with the Mystery Crate Mayhem crew. Play against bots, or with friends online using a 4-letter table code.

## Put it on GitHub Pages

1. Sign in at https://github.com and click **New repository**. Name it, for example, `mystery-crate-poker`, and make it **Public**.
2. On the new repository page, click **uploading an existing file**.
3. Drag in everything from this folder: `index.html`, `README.md` and `.nojekyll`. Click **Commit changes**.
   - `.nojekyll` is a hidden file. On a Mac press Cmd+Shift+. in Finder to see it; on Windows turn on View > Hidden items. The game still works without it.
4. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**, then click **Save**.
5. After a minute or two the page shows your game's address, like `https://your-name.github.io/mystery-crate-poker/`.

## Play with friends

- Send friends the game's address.
- One person clicks **Host a table** and reads out the 4-letter code.
- Everyone else types the code and clicks **Join**.
- The host can add bots to fill empty seats (up to 8 players), then clicks **Deal first hand**.
- The host's browser runs the game, so the host needs to keep the tab open.

Online play connects players directly, browser to browser (WebRTC, using the free PeerJS service to find each other). A few school or office networks block this; if a friend can't join, try another network or a phone hotspot.

## Controls

- Drag to look around; double-click to look straight ahead again.
- **F** fold, **C** check or call, **R** raise.
- Tap an emoji to react.
