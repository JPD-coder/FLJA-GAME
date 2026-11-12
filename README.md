# Fantasy League Jai Alai

A browser jai alai game: singles and doubles, five shots (Saque, Pelotazo, Rebota, Cortada, Costado), league and World Cup teams, and online two-player matches.

- **Play:** open `index.html` (GitHub Pages serves it at the repository address).
- **Views:** the setup screen has a View choice (70s Vintage, 80s Vintage, 20s Vintage, Side Court, Aerial Court); the View button changes view during a match.
- **Original look:** the earlier version with the drawn players and first fronton is kept in [`original/`](original/) and is playable at `/original/`.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole game: rules, drawing, controls and online play |
| `fronton6.jpg` | The court artwork, with sponsor panels and wall logo |
| `sprites.png` | The player in eight poses; recolored per team in the browser |
| `aerial-view.jpg` | Court artwork for the Aerial Court view |
| `fronton5.jpg` | The original fronton, used by the 20s Vintage view (the 70s and 80s Vintage views are drawn in code and need no picture) |
| `sprites-back.png` | The player seen from behind, used by the Aerial Court view |
| `brand.png`, `team-*.png`, `logo-*.png` | Game and club logos |
| `original/` | The previous look, complete and self-contained |

Online matches and the anonymous play counter use a small relay hosted on Railway; its address is set at the top of `index.html`.
