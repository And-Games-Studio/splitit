# Split It! website

The public pages of Split It!, served by GitHub Pages at https://and-games-studio.github.io/splitit/

- `index.html`: home page.
- `privacy/`: privacy policy (linked from the Play Store listing and the OAuth consent screen).
- `delete/`: how to have an account and its data deleted (Google Play's account deletion requirement).
- `room/`: invite links shared from the game (`room/?r=ABCDE`). On Android it opens the game in that room through an intent link, or offers the Play Store when the game isn't installed.

Plain HTML and CSS, no build step. The Fredoka font (SIL Open Font License, `fonts/OFL.txt`) is served from here, so the site makes no requests to other servers.
