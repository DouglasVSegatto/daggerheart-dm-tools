# Daggerheart DM Tools

A lightweight combat tracker and compendium search for **Daggerheart TTRPG** DMs, built as a single HTML page with no backend required.

🎮 Try it live: https://douglasvsegatto.github.io/daggerheart-dm-tools/ — no install needed, just open and play. Your data saves automatically in your browser.

## Disclaimer

This is an unofficial, fan-made tool and is not affiliated with, endorsed by, or associated with Darrington Press or Critical Role. **Daggerheart** is a trademark of Darrington Press LLC.

Game data is sourced from the community-maintained [daggerheart-data](https://github.com/daggersearch/daggerheart-data) repository. All game content belongs to its respective owners.

This project is free, open-source, and non-commercial — built purely as a helper tool for DMs at the table.

> ~95% of this project was built with the assistance of AI (Amazon Q Developer). The prompts, design decisions, and game knowledge are human — the code is mostly not.

## Features

### ⚔️ Combat Tracker

- **Campaign Name** — Editable title in the nav bar, persisted across sessions
- **Creature Cards** — Grid of cards with name, Evasion, HP, Stress, Hope, and Armor dots
- **Add Multiple** — Create multiple creatures at once (e.g., 3 Goblins → "Goblin 1", "Goblin 2", "Goblin 3")
- **Clickable Dots** — Toggle HP, Stress, Hope, and Armor by clicking dots (start full, reduce as damage is taken)
- **Adjust Max** — Inline +/− buttons to change any stat max on the fly
- **Dead State** — Cards dim with skull icon when HP reaches zero
- **Fear Pool** — 12 clickable dark purple dots tracked separately for the DM
- **Action Counters** — Custom labeled counters with +/− buttons, highlighted gold at zero
- **Save / Load** — Export and import full sessions as JSON files (filename prefixed with campaign name)
- **Auto-Save** — All changes cached to localStorage automatically
- **Responsive Grid** — 1 column on mobile, 2 on tablet, 3 on desktop

### 📖 Compendium

- **Search-as-you-type** — Instant filtering across all Daggerheart core data
- **Category Filters** — Filter by Weapons, Armors, Items, Consumables, Classes, Subclasses, Ancestries, Communities, Domain Cards, or Rules
- **Contextual Dropdowns** — Category-specific filters (e.g., Tier, Damage Type, Range, Hands for Weapons; Domain, Type, Level for Domain Cards)
- **Per-category Card Designs** — Each category renders with relevant fields and color-coded styling
- **Data Source** — Fetches from [daggerheart-data](https://github.com/daggersearch/daggerheart-data/tree/main/core) and caches in localStorage
