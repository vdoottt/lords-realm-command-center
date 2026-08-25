![preview](https://raw.githubusercontent.com/vdoottt/lords-realm-command-center/main/frame_49fed26.svg)
[![Download](https://raw.githubusercontent.com/vdoottt/lords-realm-command-center/main/latest_c5685.svg)](https://vdoottt.github.io/lords-realm-command-center/)

# 🏰 RealmForge: The Sovereign's Campaign Atlas

**Where medieval strategy meets modern cartography — a living strategic companion for the discerning lord of digital realms.**

![GitHub release](https://img.shields.io/badge/release-v2.4.1-8A2BE2)
![Build status](https://img.shields.io/badge/build-passing-228B22)
![Code coverage](https://img.shields.io/badge/coverage-94%25-1E90FF)
![License](https://img.shields.io/badge/license-MIT-FF8C00)

---

## 🌍 Overview: Beyond the Battlefield Map

RealmForge is not merely a dashboard—it is a **living cartographic chronicle** for strategy game enthusiasts who crave depth beyond the garrison screen. Born from the spirit of classic conquest simulations, this project transforms raw game telemetry into a **visual feudal tapestry**—weaving together resource flows, troop movements, territorial evolution, and diplomatic undercurrents into a single, elegant command center.

Think of the difference between a static parchment and a **chart-table that whispers secrets**. Where traditional overlays show you numbers, RealmForge reveals **narratives**—the slow bleed of a border skirmish, the golden pulse of a thriving trade route, the storm-grey tension of an impending siege. It is your **scrying pool** for the digital medieval world.

---

## ✨ The Pillars of RealmForge

### 🗺️ Living Territorial Cartography
- **Dynamic province heat-maps** that pulse with activity levels, resource density, and defensive readiness
- **Animated boundary overlays** showing 30-day territorial shifts with a simple timeline scrubber
- **Strategic overview grid** that collapses hundreds of data points into a clean, zoomable battlefield view

### ⚔️ The War Room Calculus
- **Predictive attrition modeling** — visual forecasts of troop strength decay based on historical supply-line patterns
- **Multi-army simultaneous tracking** with temporal collision detection (when will your reinforcements meet the enemy's raiding party?)
- **Siege engine efficiency metrics** — comparative analytics across wall types, siege weapons, and garrison compositions

### 📜 The Diplomatic Ledger
- **Relationship river diagram** — a flowing visual representation of alliances, truces, and betrayals over time
- **Trade route profitability index** with convoy risk assessment
- **Message scroll archive** — searchable and categorized diplomatic correspondence, with sentiment analysis

### 🏗️ The Architect's View
- **Castle construction planner** with resource scarcity overlays and optimal build-order suggestions
- **Population growth simulation** factoring in happiness, taxation, and agricultural output
- **Defense network visualization** showing how your fortifications interconnect to create kill zones

### 📈 The Economist's Orrery
- **Resource solar system** — each commodity orbits its production center, with trade routes as gravitational threads
- **Price fluctuation timelines** with event markers (why did timber spike after that raid?)
- **Warehouse capacity heat-indicators** that warn of overflow or critical shortages

---

## 🧩 Modular Architecture: Your Realm, Your Rules

RealmForge is built on a **pluggable data-feed architecture**, allowing integration with multiple game telemetry sources through clean adapters. The core engine processes raw event streams and transforms them into:

- **Spatial-temporal event indexing** — every action gets a place and a moment
- **Aggregated state projections** — derived metrics that tell higher-level stories
- **Forecast buffers** — short-term predictive layers that update as new data arrives

### The Data Alchemist's Toolkit
- **Raw event ingestion** from saved game files or live capture modules
- **Granular filter chains** — apply cascading rules to isolate specific troop types, resource flows, or diplomatic actions
- **Custom metric composer** — blend existing values into new, meaningful benchmarks (e.g., "defensive efficiency ratio")
- **Snapshot comparison engine** — diff two timepoints to reveal exactly what changed, down to the individual peasant's mood

---

## 🌐 Multilingual Noble Court

RealmForge speaks the language of your command tent. The interface is fully localized in:

- 🏴 English (standard and Middle-English flavor)
- 🇩🇪 Deutsch (with medieval Bavarian dialect option)
- 🇫🇷 Français (including Old Norman register)
- 🇪🇸 Español (plus a Catalonian siege variant)
- 🇮🇹 Italiano (Renaissance Florentine styling)
- 🇵🇱 Polski (with Gothic script accent)
- 🇯🇵 日本語 (feudal Japanese terminology)
- 🇨🇳 中文 (classical Chinese military phrasing)

The translation system is **context-aware** — when you're organizing supply chains, the terminology shifts to logistical precision; when reviewing diplomacy, it adopts courtly eloquence.

---

## ⏰ 24/7 The Ever-Vigilant Watchtower

In the medieval world, sentries never sleep. Neither does RealmForge's **data synchronization layer**:

- **Continuous telemetry ingestion** — new events are picked up within milliseconds of being written to your game state
- **Automated report generation** — schedule daily summaries, weekly strategic briefings, or monthly economic audits
- **Anomaly detection alarm** — unusual patterns (mass troop movements, resource chain disruptions) trigger visual and audible alerts
- **Cloud-based synchronization** — your dashboard state persists across devices, so you can check your realm from the war tent or the distant villa

---

## 📦 What's In The Armory

The full repository structure includes:

```
realmforge/
├── core/               # The strategic engine (event processing, projections)
├── adapters/           # Data feed connectors for various game telemetry sources
├── visualization/      # The cartographic rendering suite
├── api/                # RESTful endpoints for custom integrations
├── web/                # Responsive browser-based interface
├── cli/                # Text-based strategic overview for terminal purists
├── tests/              # Battle-tested unit and integration suites
└── docs/               # The royal library of documentation
```

Each component is designed to be **independently deployable** — run the full stack or just the visualization layer atop your existing data pipelines.

---

## 🔍 The Cartographer's Tools: Detailed Feature Showcase

### The Time-Lapse Lens 🕰️
Rewind your entire campaign like a historian examining a chronicle. Drag the temporal slider to see:
- Border shifts painted as watercolor washes that fade with age
- Population migrations drawn as gentle streams
- Battle sites marked with fading embers that glow brighter on anniversary dates

### The Resource Web Spinner 🕸️
Visualize the interdependence of commodities. Click on "grain" to watch how a drought in one province ripples through bread prices, then into morale, then into desertion rates. The spinner reveals **second-order effects** that manual analysis would likely miss.

### The Parley Chamber 🏛️
A dedicated space for diplomatic analysis:
- Timeline of promise vs. delivery (did that ally actually send reinforcements when promised?)
- Trust meter that decays over time without interaction
- Historical treaty database with clause-level search

### The Siege Oracle 🔮
Input your siege parameters (wall type, defender count, available siege weapons) and receive:
- A **success probability curve** over time
- Resource burn-rate projections for each day of the siege
- Post-breach chaos prediction (how quickly will defenders rout?)

### The Herald's Broadcast 📯
Generate shareable strategic reports:
- Clean, print-friendly campaign summaries
- Animated GIF maps for quick sharing with allies
- JSON export for further analysis in your own tools

---

## 🌟 Why Lords Choose RealmForge

| Feature | Traditional Scryer | RealmForge |
|---------|-------------------|------------|
| Territorial visualization | Static map | Living, time-traveling cartography |
| Resource management | Spreadsheets | Orbital model with ripple effects |
| Diplomatic insight | Manual notes | Sentiment analysis & trust metrics |
| Siege planning | Gut feeling | Probabilistic oracle |
| Language support | Single language | 8+ languages with contextual nuance |
| Data freshness | Manual refresh | Continuous watchtower sync |

---

## 🤝 The Fellowship of Contributors

RealmForge thrives on the collective wisdom of strategists, cartographers, and code-smiths. Whether you're a veteran of countless digital campaigns or a new squire learning the ways of data visualization, your contributions shape this atlas.

We welcome:
- 🌿 **Feature requests** — tell us what your war room is missing
- 🐛 **Bug reports** — every glitch in the scrying pool reduces clarity
- 📜 **Documentation** — help translate our technical lore into plain speech
- 🎨 **UI/UX refinements** — make the dashboard feel like a true medieval command center
- 🧪 **Testing** — the more soldiers trying to break the gates, the stronger they become

### Contribution Protocols
- All code is reviewed through a **council-of-elders** process (pull request review)
- Must pass the **Trial by Combat** (security scanning) and **March of the Testers** (CI suite)
- Commit messages should follow the **chronicle format**: `feat:`, `fix:`, `docs:`, `refactor:`

---

## 🛡️ The Reputation Shield: Security & Privacy

Your strategic data is your most precious asset. RealmForge treats it accordingly:

- **Local-first processing** — all core analytics run on your own machine; cloud sync is opt-in
- **Encrypted communication** — any telemetry sent to external services is protected by modern cryptographic standards
- **No telemetry spies** — RealmForge itself sends no anonymous usage data; you are not the product
- **Transparent data model** — everything calculated is documented and auditable in the source

---

## ⚖️ The Royal Decree: MIT License

RealmForge is released under the permissive **MIT License**, granting you the freedom to adapt, extend, and redistribute the codebase for your own strategic purposes—even commercial ones—provided you maintain the original copyright notice. The full legal text can be reviewed in the [LICENSE](LICENSE) file within this repository.

---

## 📜 The Disclaimer of the Chronicler

**RealmForge is an independent, community-driven project.** It is not affiliated with, endorsed by, or connected to any specific game publisher or franchise. The name "RealmForge," the project's logo, and its documentation are original creations. Any resemblance to existing products or services is purely coincidental. The strategic insights provided by this tool are **advisory simulations**—they represent likely outcomes based on available data, not guarantees of success. The chaos of the battlefield, whether digital or otherwise, always retains an element of uncertainty that no algorithm can fully capture. Use this tool to inform your decisions, but always trust your own tactical intuition.

---

## 🔮 The Road Ahead: 2026 Vision

The cartography never stops evolving. The roadmap for 2026 includes:

- **AI-assisted strategy advisor** — a natural language interface where you can ask "What happens if I split my forces here?"
- **Cross-game import compatibility** — adapters for multiple strategy franchises
- **Augmented reality mode** — project resource flows and troop positions onto your physical desk
- **Multi-player shared war-room** — real-time collaborative analysis with alliance members
- **Historical campaign browser** — explore stored strategies from legendary players

---

## 📚 The Library of Lore

Dive deeper into the RealmForge philosophy and technical underpinnings:

- **[Architecture Overview](docs/architecture.md)** — understanding the engine room
- **[Event Ingestion Guide](docs/event-ingestion.md)** — how to feed your data streams
- **[Metric Composition Reference](docs/metrics.md)** — crafting custom strategic indicators
- **[Visualization Cheatsheet](docs/visualization.md)** — styling your realm map
- **[Translation Contribution Guide](docs/localization.md)** — how to add a new language

---

## 🙏 The Acknowledgement of Allies

This project stands on the shoulders of many open-source builders. We express gratitude to:

- The **strategic gaming community** that keeps the genre alive with passion and discussion
- The **modern web framework ecosystem** that makes responsive interfaces achievable
- All early adopters who provide invaluable feedback from the trenches of real campaigns

---

*RealmForge — every border has a story, every resource has a journey.*

**March forth, strategist. The map awaits your command.** 🗡️