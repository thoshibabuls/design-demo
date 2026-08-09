# Direction demo — pick one, then we build it

Open **`index.html`** in a browser. Press **1 2 3 4** (or use the bar at the bottom) to
swap between four complete design directions on the same page. **Notes** opens the
thesis, type stack, signature and honest cost of whichever one you are looking at.

`?d=b` in the URL opens straight into a direction, so you can send someone a link to one.

`previews/` has a flat PNG of each hero plus `compare.png` — the four side by side, for
looking at on a phone without opening anything.

---

## What changes between directions

Not just colour. Each one swaps the palette, both typefaces, the rule weights, the
density, the edge treatment (radius, shadow, outline), and the **marker** — the small
device that flags the one line in a block that matters.

| | Direction | Field | Type | Material | Signature |
|---|---|---|---|---|---|
| 1 | **Call sheet** | Script-revision paper stocks | Archivo 900 + IBM Plex Mono | 2px ink rules, zero radius, zero shadow | The stock colour *is* the message — blue is the schedule, goldenrod is money, green is you're in. Green revision asterisk in the margin. |
| 2 | **Hard light** | Pale limewash green | Archivo alone, three widths | Hard shadow, 6px straight down, zero blur | One sun, fixed overhead. Nothing has an outline. Red tally light = someone is recording. |
| 3 | **Wildposting** | Newsprint | Anybody + Familjen Grotesk + DM Mono | 3px rules, halftone, everything a degree off square | Two-ink misregistration. Headlines print twice, slightly wrong. |
| 4 | **Edit bay** | Graphite | Instrument Sans + Martian Mono | 1px guide rules, 2px radius, no shadow | The page is framed like a monitor: corner ticks, a guide across the hero, running timecode. |

**1 is the brand you already own** (`brand/BRAND_GUIDE.md`, ~40 shipped social assets).
Choosing anything else means those assets and the page stop matching — that is the real
cost, and it is worth saying out loud before picking.

**2 is what `PLAN_LANDING_PAGE_V2.md` chose.** Seeing it next to the other three is the
point of this file.

1 and 2 are cousins from a thumbnail — both light, both Archivo. Look at them full size
before deciding they are the same; the accent, the field temperature and the material are
completely different arguments.

---

## About the copy

Every line is real. Nothing says `[headline here]`. Sources: the story deck, the
prototype, and `PLAN_LANDING_PAGE_V2.md`.

**Where the prototype and the plan disagreed, the plan wins.** So this demo says:

- **12 noon to 7 PM**, not 10 to 7
- **Lunch is free**, and you eat it with your captain
- **2 to 5 minute** films, not 3 to 5
- **Saturday and Sunday**, not Saturday only
- **Resource person** and **captain**, not "mentor"

**Three things from the prototype are deliberately not here:**

1. **The three student films.** No batch has run, so *The Last Bus*, *Amma's Recipe* and
   *Signal Lost* do not exist. That section is an honest empty state instead, and it reads
   better than a fake testimonial would.
2. **Seat counts.** Nothing says "9 seats left" until `seatsConfirmed` is genuinely true.
3. **The ₹999 masterclass and the ₹16,999 AI Intensive.** Neither appears in any approved
   source, so neither is priced here.

Still open: **the Sunday founding price.** `config.js` says ₹1,499 and the prototype's own
dated card says ₹1,999 — inside the same file. This demo uses **₹1,499** throughout, which
makes both founding days the same number and makes the ₹500 both-days discount land at
**₹2,498**. If it should be ₹1,999, every price on the page moves.

---

## Quality floor, already in

Not a promise — it is in the file. Keyboard focus is visible on everything, the FAQ is real
`<details>` so it works with JS off, `prefers-reduced-motion` is honoured, the layout goes
to one column with no horizontal scroll at 390px, and every text-on-surface pair in all four
directions clears 4.5:1.

Fonts load from Google here because it is a demo. Production self-hosts them — see
`PLAN_LANDING_PAGE_V2.md` §11.2.
