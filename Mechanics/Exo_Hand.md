# The Two-Doctrine Exo-Hand

> **Source:** CP-2 (gear Item rail) + Imago exo-suits.

## The Signature Asset

The demo's signature gear is an **exo-mechanical hand** — a form-fitting exo-suit gauntlet, 20 CP, `gear` item, Size Rank 0. Two doctrines, one chassis (mirrors psycho-frame/skiff/staff/harp/blade):

| Doctrine | Item | Effect | Flavor |
|---|---|---|---|
| **GEO Storm Exo-Hand** | `imago_storm_hand` | `{"kind":"stat_mod","acv_bonus":2,"ar":4,"note":"GEO Storm Police exo-suit gauntlet"}` | The legal lane — the World Police's gauntlet |
| **Fault-Zone Scrapper Hand** | `imago_scrapper_hand` | Same bonus + `Defect: Wanted` returning 2 CP → `Weapon Enhancement: Overcharge` | The forsaken lane — the gang's overclocked gauntlet |

Both: 20 CP, rank C, `item_type: gear`, granted as starting gear (not a market buyout).

## Attributes

- Storm hand: exo-suit gauntlet (ACV +2, AR 4 via `stat_mod`)
- Scrapper hand: overclocked, spikes power (Overcharge enhancement)

## Engine Path

One `gear` row per doctrine in the `items` table, `effect_json` structured for `models.py`. No new engine field — exactly the CP-2 rail from Enid (chassis) / Cathedral (skiff) / Ikaris (staff) / Aradia (harp) / Bazaroth (blade).