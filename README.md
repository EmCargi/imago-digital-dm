# 💿 Imago: Reality Punk — Game Disc for Chronos Core

*The reality-punk world. GEO world government, neomorph pet-battles, the Ikarion VR gate to Ikaris, fault-zone gangs, and the Xyconal menace.*

> **Source:** BESM 4e Chapter 14 (Anime Multiverse) — First-party canon, no third-party IP.
> All content authored from the canon hooks. Regenerable via the Chronos engine.

---

## 🎮 Boot (when ready)

```text
/setting besm_imago       # swap discs in the TUI
/roster                      # Credential column
/module ikarion_breach.json             # default starter module
```

| Contract layer | Status |
|---|---|
| **1 · Registration** | ✅ `besm_imago` in `config/settings.json` → `ikarion_breach.json` |
| **2 · Module** | ✅ `modules/ikarion_breach.json` (validator-passed) |
| **3 · Roster** | ✅ Starter characters authored (`Characters/`, 50 CP, `besm_imago`) |
| **4 · Economy** | ✅ Seed catalog + chassis as `Item` |
| **5 · Lore Vault** | 🏗️ `World/` `Characters/` `Factions/` `Locations/` `Mechanics/` |

> **Status: SCAFFOLDED** — disc directory + proposal exist. Layers 1–5 wired via Chronos Core engine.

## 🗂️ Structure

```
imago-digital-dm/
├── README.md               ← this home page
├── Characters/             ← PC/NPC sheets (besm_imago)
├── data/                   ← roster DB + catalog
├── Factions/               ← organizations & groups
├── Locations/              ← region & landmark sheets
├── Mechanics/              ← system rules & supplements
├── modules/                ← playable labyrinth modules
├── scripts/                ← import/parser utilities
└── World/                  ← lore vault
```

---

*Disc for the Chronos Core console. Swap via `/setting besm_imago`.*
