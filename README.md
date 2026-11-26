# UTD Campus Run

A location-drill game for UTD Campus EMS. Responders learn the UT Dallas campus by naming and finding buildings, parking, apartment phases and fields on the official campus map.

**Play:** https://sarvesh-r8.github.io/UTD-Campus-Run/

## Modes
- **Name It**: a location is circled on the map; type its code or full name (e.g. `SSB` or "Student Services Building").
- **Find It**: the game names a location; tap it on the map.
- **Full Shift**: 10 calls mixing both.

Labels are hidden during questions. **Study map** shows every location with its full name.

## Difficulty
| Difficulty | Includes | Multiplier |
|---|---|---|
| Easy | Academic buildings, residence halls, apartment phases | ×1 |
| Medium | Easy + parking structures and lots | ×1.5 |
| Hard | Everything, including fields and apartment building numbers | ×2 |

Easy and Medium show apartment building numbers and ask for the phase. Hard hides the numbers and asks for them.

## Points (per correct answer)
| Category | Easy | Medium | Hard |
|---|---|---|---|
| Academic buildings | 10 | 15 | 20 |
| Residence halls & housing | 10 | 15 | 20 |
| Apartment phases | 15 | 23 | 30 |
| Parking structures | — | 23 | 30 |
| Parking lots | — | 23 | 30 |
| Athletics & fields | — | — | 40 |
| Apartment buildings | — | — | 50 |

Find It pays 80%, a hint halves the value, fast answers earn up to +50%, and streaks of 3+ add up to +25.

Best scores are saved in each player's browser.

## Files
- `index.html`: the whole game (no build step)
- `map-labeled.jpg`, `map-blank.jpg`, `map-blank-em.jpg`: the campus map with labels, with all labels hidden (Hard), and with building numbers kept (Easy/Medium)
- `ems-logo.png`: UTD Campus EMS logo

Map: UT Dallas campus map, updated 02.05.24. Check map.utdallas.edu for the latest.
