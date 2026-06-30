# Daggerheart DM Tools

A lightweight creature/NPC tracker and compendium search for **Daggerheart TTRPG** DMs, built as a single HTML page with no backend required.

🎮 Try it live: https://douglasvsegatto.github.io/daggerheart-dm-tools/ — no install needed, just open and play. Your data saves automatically in your browser.

## Features

### ⚔️ Tracker

- **Creature Cards** — Grid of cards showing name, HP dots, and Stress dots
- **Add Multiple** — Create multiple creatures at once (e.g., 3 Goblins → "Goblin 1", "Goblin 2", "Goblin 3")
- **Clickable Dots** — Toggle HP and Stress by clicking dots (start full, reduce as damage is taken)
- **Adjust Max** — Inline +/− buttons to change HP or Stress max on the fly
- **Dead State** — Cards dim with skull icon when HP reaches zero
- **Auto-Save** — All changes cached to localStorage automatically
- **Responsive Grid** — 1 column on mobile, 2 on tablet, 3 on desktop

### 📖 Compendium

- **Search-as-you-type** — Instant filtering across all Daggerheart core data
- **Category Filters** — Filter by Weapons, Armors, Items, Consumables, Classes, Subclasses, Ancestries, Communities, Domain Cards, or Rules
- **Contextual Dropdowns** — Category-specific filters (e.g., Tier, Damage Type, Range, Hands for Weapons; Domain, Type, Level for Domain Cards)
- **Per-category Card Designs** — Each category renders with relevant fields and color-coded styling
- **Data Source** — Fetches from [daggerheart-data](https://github.com/daggersearch/daggerheart-data/tree/main/core) and caches in localStorage
