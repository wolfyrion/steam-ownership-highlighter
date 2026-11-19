# Steam Ownership Highlighter

A Tampermonkey / Violentmonkey userscript. It adds Steam ownership and wishlist badges on SteamGifts, r/GameDeals, r/FreeGameFindings, GG.deals, IsThereAnyDeal, Humble Bundle, Fanatical, IndieGala and Green Man Gaming. On stores that don't show Steam app IDs, it matches games by name. Hover a game to see Steam and ITAD prices. It can also filter out rows for games you already own.

## Installation

1. Install [Tampermonkey](https://www.tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/).
2. 👉 **[Install Script](https://raw.githubusercontent.com/wolfyrion/steam-ownership-highlighter/main/steam-ownership-highlighter.user.js)**

The script updates automatically from this repo.

## Setup

- Log in to Steam in the same browser. The script reads your owned and wishlisted games from the Steam store.
- For ITAD prices, enter an IsThereAnyDeal API key in the script's settings. This is optional.
- Settings are in the Tampermonkey menu while you're on a supported site.

## Issues

Report bugs or ask for features in [Issues](https://github.com/wolfyrion/steam-ownership-highlighter/issues).

More scripts: [wolfyrion/tampermonkey-scripts](https://github.com/wolfyrion/tampermonkey-scripts)
