# Kinship — brand concept

## The reference

**Nevin Aladağ, *Pattern Kinship*** (ongoing series) —
<https://harn.emuseum.com/objects/25229/pattern-kinship-bubbles-pingpong>

The series takes ornament from traditions and centuries that **could never
actually have met** and brings it into one silhouette. Standing in front of it
you stop reading "Ottoman" and "Bauhaus" and start seeing that the chevron in
one is the chevron in the other. Aladağ has described this as work about
hybridity and belonging, drawn from her own experience as an immigrant, and
about undoing a predetermined gaze that sorts ornament into "oriental" and
"western".

## Why it fits akinn

**Akin** means *related to; of the same kind*. The name is already a claim about
relatedness, and the pattern is that claim rendered as a graphic.

The useful property is that kinship here is **demonstrated, not asserted**.
Nothing says "we bring people together." You look at the mark and see things
that are obviously different and just as obviously family.

---

## The copyright question

Not legal advice — get a lawyer's sign-off before this ships. But the shape of
the analysis is unusually clear.

### Not hers to own

| | Why |
| --- | --- |
| **The concept** | "Combine ornament from traditions that never met into one form" is an *idea*. The idea/expression dichotomy means ideas aren't copyrightable, however good. |
| **The source ornament** | Hexagonal net, quatrefoil, Greek key, mashrabiya lattice, seigaiha scales, girih stars — all centuries old, all public domain. She didn't invent them; she went and got them. So can we. |
| **Style** | Not copyrightable. Work "in the same tradition" is legal. |
| **Technique** | Waterjet cutting; tiling a region with a repeat. |

### Hers

**The specific composition** — that arrangement, those cells, those choices.
Copy the arrangement and it's infringement.

### The operating rule

**Go to her sources, not her results.** Two designers drawing on the same
public-domain ornament produce related-looking work without either copying the
other. That is how ornament has always worked.

### The one thing we deliberately gave up

Her **sweeping black curves** — free-drawn, gestural, cutting across the discs
independently of the geometry beneath them. That is her signature move, the
thing that makes a piece read as *an Aladağ*, and it is the most expressive and
least functional element, therefore the most protectable. We don't use it. Our
cell boundaries come only from disc overlap: computed, not composed.

---

## The system

A mark is generated from a six-character seed.

| Rule | What it encodes |
| --- | --- |
| **Overlap makes the cells.** Discs are packed until they form one connected silhouette. Every region exists *because* two discs met; no cell has a boundary of its own. | Structure as a consequence of relation, not a decoration applied to it. |
| **Strict partition.** Disc *i* owns whatever no higher-indexed disc claims. Those regions tile the silhouette exactly — every point lands in one cell and only one, however deep the stack. Each is then split against the first disc below it that reaches in. | No gaps, no double-painting, arbitrary overlap depth. |
| **Cut, not printed.** Every tiling is stroke and void; the ground shows through. | The mark behaves like pierced metal, not ink. It never blocks what's behind it. |
| **Two scale registers.** A cell gets either a fine mesh or a bold motif, never a middle that averages into grey. | Density contrast is what makes the eye keep exploring. |
| **One hot cell.** Six chalky colours per mark and exactly one saturated, placed by the seed. | Without it the mark goes polite; with two it goes loud. |

### Tiling vocabulary

Ten seamless repeats, constructed from scratch. Each arose *independently* in
several traditions — which is the whole argument: they were already kin before
anyone arranged them.

Square net · diagonal grid · circle net · quatrefoil · chevron · stepped fret ·
scales · dot field · star lattice · ogee net

### Reduction

| Level | Discs | Coarsen | Use |
| --- | --- | --- | --- |
| Full | 10 | 1× | Entry screen, posters, packaging |
| Mark | 6 | 1.7× | Navigation, business card |
| Bug | 4 | 2.8× | Favicon, avatar, stamp |

Tile scale is coarsened as disc count drops, so the mark stays legible instead
of dissolving into grey.

## As a website entry

`index.html` is the working entry screen.

- Cells fade in one at a time, the disc outlines land last — the silhouette
  resolves in front of you.
- **Every visitor gets a different mark. Every visitor gets the same family.**
  The seed is shown and written to the URL: `akinn.com/?seed=n4kp2r`.
- *Another* reseeds. The specimen sheet shows the reduction row and eight
  siblings; clicking one adopts it. A final section shows the ten source
  tilings plainly, with where each comes from.
- The accent colour driving seed label, focus rings and hover is pulled from
  the current mark's hot cell.

## Open questions

1. **What does akinn actually do?** The copy is deliberately thin for that
   reason. Sector and audience will change the tagline and probably the
   neutrals.
2. **Persist the seed per visitor** (it becomes *your* mark — an identity) or
   reroll every visit (a welcome)? Currently rerolls.
3. **True favicon.** The bug holds at ~56px; 16px likely wants a hand-tuned
   3-disc version rather than a generated one.
4. **The other route.** Commissioning or licensing from the artist is available,
   more respectful, and often cheaper than the legal comfort of going it alone.
   Worth pricing before committing to homage.
