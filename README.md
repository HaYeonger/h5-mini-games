# H5 Mini Games

Ten original single-file HTML5 mini-games. Each game is one self-contained `.html` file: zero dependencies, no build step, no network requests, no external assets. Open it in any modern browser — desktop or mobile — and play.

Every game ships with full Chinese/English bilingual support and a one-tap language toggle in the top-right corner. The default language follows the browser locale.

## Games

| # | Game | Genre | Premise |
|---|------|-------|---------|
| 1 | Prompt Alchemy (提示词炼金术) | Strategy puzzle | Work as a prompt engineer tuning a simulated local LLM. Score 80+ (out of 120) to clear each task; exceeding the token budget multiplies your score by 0.85. |
| 2 | Insomnia (失眠) | Relaxation | Seven nights. Let intrusive thoughts drift by without engaging them, build drowsiness, and fall asleep. Watch your heart rate and breathing rhythm. |
| 3 | The 4 AM Convenience Store (凌晨四点的便利店) | Narrative | Night shift at a 24-hour convenience store. Serve 12 late-night customers: observe, ask, respond — and bring each one's worries down to 10 or below. |
| 4 | Midlife Crisis Simulator (中年危机模拟器) | Life sim | Live from age 35 to 50. Career, family, health, and savings pull in different directions; every choice has a cost. Your epitaph is written at the end. |
| 5 | Left on Read (已读不回) | Chat sim | Free-text conversations with three contacts. There are no preset options — tone is everything, and relationships move with every message. |
| 6 | Code Review Hell (CodeReview地狱) | Puzzle | Find the bug hiding in each pull request. Skills are limited; legacy code is not. Survive production incidents. |
| 7 | Hold the Wallet (守住钱包) | Tower defense | Defend your savings against waves of 618, Double 11, and Black Friday sales. Hold the ¥80,000 line. |
| 8 | Holiday Party Survival (年会求生) | Social survival | Ten rounds at the office holiday party. Manage alcohol tolerance, composure, boss favor, and popularity — and leave with dignity. |
| 9 | Rent Adventure: New York (租房大冒险·纽约篇) | Life sim | Thirty-six months renting across New York City. Browse listings, handle landlords and roommates, work side gigs, and save enough for a down payment. |
| 10 | The Last Delivery (最后一份外卖) | Strategy | Deliver food on a typhoon night. Plan routes, mind the battery and the clock. Five endings. |

## Getting started

```sh
git clone https://github.com/HaYeonger/h5-mini-games.git
```

Open any file under `games/` in a modern browser (Chrome, Safari, Edge, Firefox). No server or build tooling required — opening via `file://` works.

## Project structure

```
h5-mini-games/
├── games/   # the ten games, one self-contained HTML file each
├── docs/    # gameplay reference
├── README.md
└── LICENSE
```

## Notes

- All content is original.
- Progress is saved to the browser's `localStorage`; clearing site data resets it.
- Save compatibility is preserved across updates (see Rent Adventure: New York).

## License

MIT — see [LICENSE](LICENSE).
