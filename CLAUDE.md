# Claude Projects — Persistent Context

## About Me
- Product designer / PM working on consumer sports/fantasy apps
- Prototyping features for a Yahoo Fantasy-style product
- Preference: build fast, match designs closely to reference PNGs, swipe-only interactions

---

## How to Start a Session
```bash
cd ~/Desktop/Claude\ Projects
claude
```
Then tell me which project to work on or start a new one.

---

## Projects

### fantasy-swipe/
**What it is:** Tinder-style sit/start decision tool for fantasy football rosters, embedded as a module inside a Yahoo Fantasy home screen.

**Stack:** Single-file vanilla HTML/CSS/JS — no build tools, no dependencies. Open `index.html` directly in a browser.

**Spec:** See `fantasy-swipe/HANDOFF.md` for full module spec, data model, design decisions, and open bugs.

**Image CDNs:**
- Headshots: `https://a.espncdn.com/i/headshots/nfl/players/full/{espnId}.png`
- Logos: `https://a.espncdn.com/i/teamlogos/nfl/500/{abbr}.png`

**Known ESPN player IDs:**
| Player | ID |
|---|---|
| Josh Allen | 3918298 |
| Patrick Mahomes | 3139477 |
| Derrick Henry | 3043078 |
| Saquon Barkley | 3929630 |
| Tyreek Hill | 3116406 |
| CeeDee Lamb | 4241389 |
| Travis Kelce | 15847 |
| Sam LaPorta | 4430027 |
| Davante Adams | 16800 |
| Jaylen Waddle | 4372016 |
| Tony Pollard | 3916148 |
| Joe Mixon | 3116385 |
| Lamar Jackson | 3916387 |
| Dak Prescott | 2577417 |
| DJ Moore | 3915416 |
| Amari Cooper | 2976499 |

---

## My Preferences
- **Communication:** Short and direct, no filler
- **Code:** Minimal, no unnecessary abstractions, edit existing files rather than creating new ones
- **Design:** Always read reference PNGs before building UI, match them closely
- **Figma:** Share frames as exported PNGs — more reliable than Figma links for design matching
- **No dark mode** on prototypes unless specified — match Yahoo's light theme
- **Prototypes** are single HTML files unless the project clearly needs more
