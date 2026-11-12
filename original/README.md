# Fantasy League Jai Alai

A browser game: two-on-two jai alai, against the computer or against a friend online.

## Put it on GitHub Pages

1. Create a new repository on GitHub (for example `fantasy-league-jai-alai`).
2. Upload every file in this folder to the repository root: `index.html` and all the image files.
3. In the repository, open Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", pick the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two the game is live at `https://<your-username>.github.io/<repository-name>/`.

Keep `index.html` and the images in the same folder.

## Playing a friend online

1. Both players open the game's web address.
2. One taps **Host a game** and reads out the four-letter code.
3. The other types the code and taps **Join**.
4. The host taps the court to start.

Online matches connect through a small relay running on Railway:
`wss://relay-production-5e78c1a2.up.railway.app/ws` (project `fantasy-league-jai-alai`, service `relay`).
The address is set near the top of `index.html` as `window.FL_RELAY`. If the relay is ever moved, change it there.
The relay stores nothing; a match exists only while both players are connected.
