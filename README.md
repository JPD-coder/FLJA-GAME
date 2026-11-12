# Fantasy League Jai Alai

A browser jai alai game: singles and doubles, five shots (Saque, Pelotazo, Rebota, Cortada, Costado), league and World Cup teams, and online two-player matches.

- **Play:** open `index.html` (GitHub Pages serves it at the repository address).
- **Views:** Play Settings has a View choice (Side, Court, Aerial); the View button changes camera during a match.
- **Original look:** the earlier version with the drawn players and first fronton is kept in [`original/`](original/) and is playable at `/original/`.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole game: rules, drawing, controls and online play |
| `fronton6.jpg` | The court artwork, with sponsor panels and wall logo |
| `sprites.png` | The player in eight poses; recolored per team in the browser |
| `court-view.jpg`, `aerial-view.jpg` | Court artwork for the Court and Aerial cameras |
| `sprites-back.png` | The player seen from behind, used by the Court and Aerial cameras |
| `brand.png`, `team-*.png`, `logo-*.png` | Game and club logos |
| `original/` | The previous look, complete and self-contained |

Online matches and the anonymous play counter use a small relay hosted on Railway; its address is set at the top of `index.html`.
