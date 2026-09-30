# DESIGN.md — TBD client name

**Status:** no direction yet · _(no direction → proposed → approved, with date and by whom)_

The rules Claude Code builds from. If a section can't be built from this file without asking,
this file is incomplete. Mirror tokens in `src/app/globals.css` (`@theme`).

## 1. Brand evidence

What already exists: logo, signage, interior, packaging, uniforms, colours and materials seen.
Tag each line [Client], [Public] or [Observed].

TBD

## 2. References

Two to five sites. For each: what to take, and what not to copy.

| Site | Take | Don't take |
| --- | --- | --- |

## 3. Direction

One paragraph: the single idea. Then 6–10 rules.

TBD

## 4. Tokens

Colour, type, spacing, radius, motion. Keep in step with `globals.css`.

TBD

## 5. Imagery

Intervention ladder. Record each asset's ceiling in `assets.csv`.

| Level | Name | What it allows |
| --- | --- | --- |
| R | Recapture | Client reshoots on phone from a shot brief |
| L0 | Original | As supplied |
| L1 | Enhance | Exposure, colour, noise, cleanup (remove stray objects), shared grade |
| L2 | Recompose | Crop, isolate, reframe, code-side art direction |
| — | **Ceiling** | **Real people, premises, products (including food) and results stop here** |
| L3 | Composite | Genuine elements combined; must not change what a customer would get |
| L4 | Generative | Extensions, backgrounds, environment; no change to claims |
| L5 | Synthetic | Textures, abstract, illustrative only |
| P | Photographer | When the gap is a real person or place and recapture can't cover it |

Crossing the ceiling on an authenticity-critical asset needs a written reason in `assets.csv` and
client sign-off. An AI disclosure does not fix an image that misleads.

## 6. Hero Lab

Comps first, then code. **Maximum three coded iterations.** Log each one.

| # | Date | What changed | Verdict |
| --- | --- | --- | --- |

Exit checklist. Every box must be yes at **both 1440 and 390** (`npm run shots`):

- [ ] Visitor knows what this is and who it's for in 5 seconds
- [ ] One primary action, visible without scrolling on mobile
- [ ] Image carries a real subject of this business
- [ ] Mobile composition was designed, not shrunk
- [ ] Type and colour follow this file
- [ ] LCP image or poster loads without animation gating it
- [ ] Would sit comfortably in the client's competitor set, and above it

## 7. Never

Banned patterns for this project.

## 8. Rejected

What was tried and why it was dropped.
