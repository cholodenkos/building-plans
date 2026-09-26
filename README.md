# Cholodenko's — Schematic Design

An eight-room bed and breakfast plus a detached three-bedroom guest house for the owner: two stories plus an attic on the inn, 1920s storybook detailing, and a circulation plan that matches the brief exactly — check-in foyer flanked by two sitting parlors, corridors from each parlor to four guest rooms per side (two per floor), a dining room and kitchen behind the foyer, and laundry, storage, and the attic stair behind the second-floor landing.

The inn is designed to **commercial (R-1) code** from the start, not a residence with extra bedrooms — eight guest rooms puts it well past Oregon's small bed-and-breakfast allowance. The guest house is an ordinary single-family residence under the **Residential Specialty Code (R-3)**, a much simpler path. Both are a **schematic design (SD) set** — massing, room layout, dimensioned stairs, and code flags — not a permit set. A licensed Oregon architect and the Jackson County Building Safety Division need to sign off on anything here before it gets built.

Every floor plan has been checked cell-by-cell against its own footprint — there is no undefined or accidentally-open space on any sheet. See [Coverage check](#coverage-check-no-undefined-space) below.

## Drawings

| Sheet | File | Description |
|---|---|---|
| A-001 | [`plans/site-diagram.svg`](plans/site-diagram.svg) | Schematic site diagram — guest house sited 65'+ from the inn, sharing a driveway (not a surveyed plot plan) |
| A-201 | [`plans/elevation.svg`](plans/elevation.svg) | Inn front elevation — flat pilasters between five arched windows, a straight-slope mansard roof, a low front dormer, a full-width awning, and a river-rock ground floor |
| A-101 | [`plans/ground-floor.svg`](plans/ground-floor.svg) | Inn ground floor — foyer, parlors, dining room, kitchen, 4 guest rooms, housekeeping storage |
| A-102 | [`plans/second-floor.svg`](plans/second-floor.svg) | Inn second floor — 4 guest rooms, spa, guest lounge, laundry, storage, attic stair, linen storage |
| A-103 | [`plans/attic.svg`](plans/attic.svg) | Inn attic — dormer reading nook, unfinished storage and mechanical space |
| A-301 | [`plans/guest-house-elevation.svg`](plans/guest-house-elevation.svg) | Guest house front elevation — plain gable roof, one round gable window, a small covered porch |
| A-302 | [`plans/guest-house-plan.svg`](plans/guest-house-plan.svg) | Guest house floor plan — 3 bed / 2 bath, single story, 1,428 sf |

Each SVG is self-contained (no external stylesheet needed) and opens cleanly in a browser or any vector editor.

## The idea

An eight-room inn should feel like a good story rather than a courthouse, so the pilasters between the upper windows are slim and flat — barely proud of the wall, closer to the seams of a dress than a colonnade. The roofline is a proper mansard with straight slopes and a low front dormer, its one window sitting just above the second-floor windows, not stranded up near the ridge. The awning stays wide and confident, the ground floor is river rock rather than coursed stone, and the palette leans on navy alongside the earth tones.

The guest house is the modest, no-frills cousin: same cream stucco and weathered-slate roof tone so the two buildings read as a set, but a plain gable roof instead of a mansard, no awning, no river rock, no pilasters. One round window in the gable peak and an arched door head are the only ornament on the whole house.

## Program, at a glance

**Inn:**
- **8 guest rooms**, all en suite (4 ground floor, 4 second floor — 2 per side per floor), 210 sf net each
- **2 sitting parlors** flanking the check-in foyer, with a small guest spa and a second-floor guest lounge (336 sf each) directly above them, flanking the stair landing
- **Dining room (336 sf) + kitchen (256 sf)** behind the foyer, between the two guest wings — dining sized larger than the kitchen, the standard ratio for a B&B serving breakfast to its own guests rather than running a full restaurant line
- **Housekeeping / linen storage**, 176 sf per wing per floor (4 rooms total) — behind the rear guest room in each wing, next to that wing's stair
- **3 levels**: 2 stories plus an attic (dormer reading nook + unfinished storage/mechanical)
- **Redundant vertical circulation**: an enclosed, 1-hour-rated stair at the end of each wing's corridor, plus an open main stair in the foyer and a second-floor hall connecting both wings — no guest room depends on a single stair

**Guest house:**
- **3 bedrooms, 2 bathrooms**, single story, 1,428 sf (42' × 34')
- Open kitchen/dining/living across the front; a hallway band behind it reaches the primary suite and two secondary bedrooms
- Sited 65'+ from the inn, not connected to it, sharing a driveway

## Dimensions checked against real numbers

The inn's footprint grew from an initial 48'-deep pass to **64' × 55'** once the stairs were run through actual riser-and-tread math instead of drawn to a plausible-looking box:

- **Floor-to-floor height:** 10'-6" (assumes ~9'-0" finished ceilings + a typical floor/ceiling assembly)
- **Stairs:** 18 risers @ 7", 17 treads @ 11", split into two flights with a 3'-8" landing — 7'-4" run + 3'-8" landing = 11'-0" of depth, which is what each stair shaft is drawn at
- **Wing stair shafts:** 8' × 11', wide enough for two 3'-8" flights side by side inside a 1-hour rated enclosure
- **Corridors:** 8'-0" clear, well past the 44" commercial minimum, and wide enough to double as the stair shaft's width without a wall jog
- **Doors:** guest room doors 3'-0" clear, main entry a 6'-0" double door
- **Building height:** grade to ridge estimated at 36'–38' — worth checking against the site's zoning height limit (commonly 35' in Jackson County residential and commercial zones) before the roof pitch is locked in

## Coverage check: no undefined space

Every room rectangle on every floor plan (inn ground floor, inn second floor, inn attic, guest house) was rasterized against its building's full footprint to confirm there is no interior square foot left uncovered. An earlier pass had exactly this problem — a 24'×14' block on the second floor was drawn as "open to below" when it wasn't actually connected to anything, which became the space the spa and guest lounge now occupy — and the same bug turned up a second time: an 11'-deep strip behind the rear guest room in each wing (below Rooms 102/104 on the ground floor, 202/204 on the second floor), 176 sf each, that had a floor and exterior walls but no assigned function or dividing wall.

Both are now fixed and named:
- **Ground floor:** a 176 sf **Housekeeping / Storage** room per wing (2 total), reached from the stair hall
- **Second floor:** a 176 sf **Linen Storage** room per wing (2 total), reached the same way

The four rooms are a genuine operational need for an 8-room inn (linens, carts, cleaning supplies) rather than filler, but the honest story is that they exist because a coverage check caught unassigned space, not because they were programmed from the start.

## The second-floor spa fits in 336 sf

The space west of the stair landing — 24' × 14', formerly framed as an owner's suite — is now a small guest spa: a private treatment table, a two-chair salon floor (hair, mani/pedi), and its own waiting area, all checked against the footprint rather than assumed:

- **Treatment room, 140 sf** (10' × 14'), walled off with its own door — a 30" × 78" massage/facial table needs roughly this much room to work around
- **Salon floor, 112 sf** (8' × 14'), split front-to-back: a hair station with mirror and counter, a mani/pedi station behind it — each station only needs 35–50 sf
- **Waiting area, 54 sf** (6' × 9'), just inside the door: a loveseat, two chairs, a small table
- **Restroom, 30 sf** — the suite's former bath, now doing double duty as the spa's restroom and linen storage

Water and drain lines already run to that wall for the bath, which helps if a pedicure basin ever needs plumbing rather than a portable bowl. Nail and hair chemicals want mechanical exhaust ventilation beyond a bathroom fan, and Oregon licenses massage therapists, cosmetologists, and nail techs separately — worth a conversation with Jackson County Building Safety and the relevant state licensing boards before build-out.

## The guest house

Converting the owner's suite to a spa meant the innkeeper's own quarters needed to go somewhere else — hence a detached house on the same property, sited well apart from the inn (65'+, see the site diagram) and sharing its driveway. Modest and no-frills by request:

- **Open kitchen / dining / living** across the front (672 sf combined), no walls between them
- **Primary suite** (18' × 13', 171 sf net) with its own bath and a door straight out to the back yard
- **Two secondary bedrooms** (130 sf and 117 sf) sharing a hall bath and a linen closet
- A single laundry closet off the kitchen; no dedicated foyer, no chimney, no fireplace — heat is mechanical
- One storybook gesture on the whole house: a round window in the gable peak and an arched front-door head, echoing the inn's arches without any of its ornament

This is an ordinary single-family residence under the Oregon Residential Specialty Code (R-3) — egress windows in every bedroom, interconnected smoke and CO alarms, standard fixture counts, far simpler than the inn's permit path. But it's a second dwelling on a commercially-used lot, which is its own question for Jackson County and Ashland planning: confirm it's allowed as an owner's residence or caretaker's dwelling before assuming it's a given.

## Jackson County, Oregon — code notes to raise early

These are flags for your architect and the county, not conclusions.

**The inn (commercial / R-1):**

- **Occupancy classification** — eight guest rooms is well past Oregon's small bed-and-breakfast allowance. This is drawn to R-1 (transient) under the Oregon Structural Specialty Code — the full commercial code, not the residential one.
- **Means of egress** — every guest room has a path to its own wing's enclosed stair and a second path across the second-floor hall to the main stair.
- **Stair & corridor construction** — wing stairs are enclosed in a 1-hour rated shaft with self-closing fire doors at the corridor (the real exit stairs); the main stair stays open to the foyer as a feature stair, not an exit. Corridor walls separating guest rooms from the corridor are 1-hour rated.
- **Fire protection** — will need automatic sprinklers (NFPA 13 or 13R), a monitored fire alarm system, interconnected smoke alarms in every guest room, and a Type I hood with automatic suppression over any grease-producing cooking equipment.
- **Vertical accessibility** — there's no elevator in this set. The usual exemption (under three stories AND under 3,000 sf per floor) needs both conditions, and this floor plate runs about 3,520 sf — over that threshold. Worth confirming whether an elevator is required to reach the second-floor rooms, guest lounge, and spa.
- **Accessibility** — an accessible route runs from parking to Room 101, the foyer, and the dining room. Room 101 is sized for a roll-in shower and a 60" turning circle. Beyond that one mobility-accessible room, ADA also requires a separate, smaller count of rooms with accessible communication features (visual/audible alarms) — typically one or two more rooms at this size.
- **Food service** — breakfast for overnight guests only is licensed differently than a full-service kitchen. Confirm with Jackson County Environmental Health / Oregon Health Authority which license applies, and the kitchen's grease interceptor sizing.
- **Building height** — see Dimensions above; confirm against the zone's height limit before the roof pitch is locked in.
- **Zoning (Ashland specifically)** — if the site is inside Ashland city limits, the Travelers' Accommodation ordinance limits unit counts in most residential zones and will likely require a Conditional Use Permit at eight rooms.
- **Site planning, now that there are two buildings** — parking needs to cover inn guests, staff, and the spa separately from the guest house's own two spaces. The guest house is sited well past any fire-separation-distance concern. If the property runs on well and septic, Oregon sizes septic systems by bedroom count — three more bedrooms adds real capacity to plan for.

**The guest house (residential / R-3):** egress windows in every bedroom, interconnected smoke and CO alarms, standard fixture counts — and confirmation from Jackson County / Ashland planning that a second dwelling is allowed on this lot alongside the inn.

Codes are adopted on a cycle and can shift between when this is drawn and when it's built — treat every item above as a question for Jackson County Building Safety and a licensed Oregon architect, not an answer.

## Materials (earth tones, with navy)

| Swatch | Use |
|---|---|
| River Rock | Inn ground-floor base — rounded, irregular fieldstone, not coursed ashlar or brick |
| Cream Stucco | Upper wall (both buildings) |
| Weathered Slate | Roof tone (both buildings) |
| Navy Canvas | Inn awning, window glass tint |
| Brass & Cordon | Inn belt course, sconces, hardware |

---

*Schematic design, prepared 26 September 2026.*
