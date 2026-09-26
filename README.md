# Cholodenko's — Schematic Design

An eight-room bed and breakfast: two stories plus an attic, 1920s storybook detailing, and a circulation plan that matches the brief exactly — check-in foyer flanked by two sitting parlors, corridors from each parlor to four guest rooms per side (two per floor), a dining room and kitchen behind the foyer, and laundry, storage, and the attic stair behind the second-floor landing.

This is designed to **commercial (R-1) code** from the start, not a residence with extra bedrooms — eight guest rooms puts it well past Oregon's small bed-and-breakfast allowance. It's a **schematic design (SD) set** — massing, room layout, dimensioned stairs, and code flags — not a permit set. A licensed Oregon architect and the Jackson County Building Safety Division need to sign off on anything here before it gets built.

## Drawings

| Sheet | File | Description |
|---|---|---|
| A-201 | [`plans/elevation.svg`](plans/elevation.svg) | Front elevation — flat pilasters between five arched windows, a straight-slope mansard roof, a low front dormer, a full-width awning, and a river-rock ground floor |
| A-101 | [`plans/ground-floor.svg`](plans/ground-floor.svg) | Ground floor — foyer, parlors, dining room, kitchen, 4 guest rooms |
| A-102 | [`plans/second-floor.svg`](plans/second-floor.svg) | Second floor — 4 guest rooms, laundry, storage, attic stair |
| A-103 | [`plans/attic.svg`](plans/attic.svg) | Attic — dormer reading nook, unfinished storage and mechanical space |

Each SVG is self-contained (no external stylesheet needed) and opens cleanly in a browser or any vector editor.

## The idea

An eight-room inn should feel like a good story rather than a courthouse, so the pilasters between the upper windows are slim and flat — barely proud of the wall, closer to the seams of a dress than a colonnade. The roofline is a proper mansard with straight slopes and a low front dormer, its one window sitting just above the second-floor windows, not stranded up near the ridge. The awning stays wide and confident, the ground floor is river rock rather than coursed stone, and the palette leans on navy alongside the earth tones.

## Program, at a glance

- **8 guest rooms**, all en suite (4 ground floor, 4 second floor — 2 per side per floor), 210 sf net each
- **2 sitting parlors** flanking the check-in foyer, with a small guest spa and a second-floor guest lounge (336 sf each) directly above them, flanking the stair landing
- **Dining room (336 sf) + kitchen (256 sf)** behind the foyer, between the two guest wings — dining sized larger than the kitchen, the standard ratio for a B&B serving breakfast to its own guests rather than running a full restaurant line
- **3 levels**: 2 stories plus an attic (dormer reading nook + unfinished storage/mechanical)
- **Redundant vertical circulation**: an enclosed, 1-hour-rated stair at the end of each wing's corridor, plus an open main stair in the foyer and a second-floor hall connecting both wings — no guest room depends on a single stair

## Dimensions checked against real numbers

The footprint grew from an initial 48'-deep pass to **64' × 55'** once the stairs were run through actual riser-and-tread math instead of drawn to a plausible-looking box:

- **Floor-to-floor height:** 10'-6" (assumes ~9'-0" finished ceilings + a typical floor/ceiling assembly)
- **Stairs:** 18 risers @ 7", 17 treads @ 11", split into two flights with a 3'-8" landing — 7'-4" run + 3'-8" landing = 11'-0" of depth, which is what each stair shaft is drawn at
- **Wing stair shafts:** 8' × 11', wide enough for two 3'-8" flights side by side inside a 1-hour rated enclosure
- **Corridors:** 8'-0" clear, well past the 44" commercial minimum, and wide enough to double as the stair shaft's width without a wall jog
- **Doors:** guest room doors 3'-0" clear, main entry a 6'-0" double door
- **Building height:** grade to ridge estimated at 36'–38' — worth checking against the site's zoning height limit (commonly 35' in Jackson County residential and commercial zones) before the roof pitch is locked in

## The second-floor spa fits in 336 sf

The space west of the stair landing — 24' × 14', formerly framed as an owner's suite — is now a small guest spa: a private treatment table, a two-chair salon floor (hair, mani/pedi), and its own waiting area, all checked against the footprint rather than assumed:

- **Treatment room, 140 sf** (10' × 14'), walled off with its own door — a 30" × 78" massage/facial table needs roughly this much room to work around
- **Salon floor, 112 sf** (8' × 14'), split front-to-back: a hair station with mirror and counter, a mani/pedi station behind it — each station only needs 35–50 sf
- **Waiting area, 54 sf** (6' × 9'), just inside the door: a loveseat, two chairs, a small table
- **Restroom, 30 sf** — the suite's former bath, now doing double duty as the spa's restroom and linen storage

Water and drain lines already run to that wall for the bath, which helps if a pedicure basin ever needs plumbing rather than a portable bowl. Nail and hair chemicals want mechanical exhaust ventilation beyond a bathroom fan, and Oregon licenses massage therapists, cosmetologists, and nail techs separately — worth a conversation with Jackson County Building Safety and the relevant state licensing boards before build-out. Converting this room from an owner's suite to a spa also means the innkeeper's own quarters need to live somewhere else on the property, worth deciding early since Ashland's ordinance leans on an on-site owner-manager.

## Jackson County, Oregon — commercial code notes to raise early

These are flags for your architect and the county, not conclusions:

- **Occupancy classification** — eight guest rooms is well past Oregon's small bed-and-breakfast allowance. This is drawn to R-1 (transient) under the Oregon Structural Specialty Code — the full commercial code, not the residential one.
- **Means of egress** — every guest room has a path to its own wing's enclosed stair and a second path across the second-floor hall to the main stair.
- **Stair & corridor construction** — wing stairs are enclosed in a 1-hour rated shaft with self-closing fire doors at the corridor (the real exit stairs); the main stair stays open to the foyer as a feature stair, not an exit. Corridor walls separating guest rooms from the corridor are 1-hour rated.
- **Fire protection** — will need automatic sprinklers (NFPA 13 or 13R), a monitored fire alarm system, and interconnected smoke alarms in every guest room.
- **Accessibility** — an accessible route from parking to Room 101, the foyer, and the dining room. Room 101's door and clearances are sized for a roll-in shower and a 60" turning circle; final hardware and route grading still need review.
- **Food service** — breakfast for overnight guests only is licensed differently than a full-service kitchen. Confirm with Jackson County Environmental Health / Oregon Health Authority before finalizing the kitchen equipment layout.
- **Building height** — see Dimensions above; confirm against the zone's height limit before the roof pitch is locked in.
- **Zoning (Ashland specifically)** — if the site is inside Ashland city limits, the Travelers' Accommodation ordinance limits unit counts in most residential zones and will likely require a Conditional Use Permit at eight rooms. Worth a planning department conversation before the drawings go further.

Codes are adopted on a cycle and can shift between when this is drawn and when it's built — treat every item above as a question for Jackson County Building Safety and a licensed Oregon architect, not an answer.

## Materials (earth tones, with navy)

| Swatch | Use |
|---|---|
| River Rock | Ground-floor base — rounded, irregular fieldstone, not coursed ashlar or brick |
| Cream Stucco | Upper wall |
| Weathered Slate | Mansard roof |
| Navy Canvas | Awning, window glass tint |
| Brass & Cordon | Belt course, sconces, hardware |

---

*Schematic design, prepared 26 September 2026.*
